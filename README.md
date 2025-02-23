# MongoDB: Unexpected Behavior with $inc within $set

This example demonstrates an incorrect usage of the MongoDB `$inc` operator within a `$set` operation, leading to unexpected behavior. The correct approach is to directly use the `$inc` operator within the update operation.

## Bug Description

The original code attempts to increment a counter field using `$inc` inside a `$set` operation. This approach does not work correctly; instead, the `$inc` operator should be used directly as an update operator.

## Solution

The solution demonstrates the correct approach of using `$inc` directly within the update operator, ensuring the counter field is correctly incremented.
