# TypeScript Type Guard and Nullish Coalescing Issue

This repository demonstrates a subtle issue with TypeScript's type guards and the handling of nullish values (null and undefined).

The `bug.ts` file contains a function that attempts to handle null values gracefully using a type guard. However, it fails to correctly handle `undefined` values, resulting in a runtime error.

The `bugSolution.ts` file provides a solution that addresses this issue by explicitly checking for both `null` and `undefined` values.

This example highlights the importance of explicitly considering all nullish values when working with optional parameters or types in TypeScript.