# Evaluation Metric Policy

## Definitions
- **Cell Recovery Accuracy (CRA)**: Recovered error cells over annotated error cells. Reported as a pooled micro rate and as a source-table macro average.
- **Clean Cell Preservation Rate (CPR)**: Originally clean cells left untouched.
- **Collateral Damage Rate (CDR)**: 1 - CPR (lower is better).

## Execution and Structural Properties
- **Execution success**: The program runs to completion without timing out.
- **Valid output**: An output table is produced.
- **Schema preservation**: The output table has the same column set as the input.
- **Exact table match**: The output table exactly matches the clean table.

## Failure Policy
A case whose output is not a valid table contributes zero recovery and is excluded from the CPR/CDR pool, because there is no modification behaviour to score.
