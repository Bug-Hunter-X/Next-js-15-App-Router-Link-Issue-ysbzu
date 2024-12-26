# Next.js 15 App Router Link Issue

This repository demonstrates a common issue encountered when migrating from the Pages Router to the App Router in Next.js 15. The problem arises from incorrect usage of the `next/link` component within the App Router's structure.

The `bug.js` file shows the initial problematic code, while `bugSolution.js` presents the corrected solution.

## Problem

In the Pages Router, a simple `next/link` component worked for navigating to routes.  However, in the App Router, this can lead to unexpected behavior, especially with dynamic segments, if not handled correctly.  The App Router necessitates a more precise approach to route definition. 

## Solution

The solution involves understanding the App Router's path structure and how to construct links accordingly.