# MongoDB Aggregation Pipeline Bug: Unexpected Results

This repository demonstrates a common error in MongoDB aggregation pipelines involving the `$group`, `$sort`, and `$limit` stages. The provided code exhibits an issue where the pipeline doesn't produce the intended outcome due to an incorrect stage order or unexpected stage interaction.

The `bug.js` file contains the erroneous code, and `bugSolution.js` offers a corrected version that addresses the error and yields the expected results. This example is useful for understanding how to efficiently use these aggregation stages to achieve desired outcomes.

## Bug Description:

The original aggregation pipeline incorrectly applies the stages, resulting in inaccurate aggregation results.  The problem stems from the interaction between the ordering of `$group`, `$sort`, and `$limit`.

## Solution:

The solution demonstrates the proper ordering and usage of the stages to ensure accurate and efficient aggregation.