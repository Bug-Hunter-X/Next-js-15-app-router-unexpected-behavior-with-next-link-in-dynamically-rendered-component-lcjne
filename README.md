# Next.js 15 app router unexpected behavior with next/link in dynamically rendered component

This repository demonstrates an uncommon bug in Next.js 15's App Router when using `next/link` within a component that's rendered dynamically.  The issue results in unexpected navigation behavior or failure to navigate correctly.

## Bug Description

The primary issue lies in how the `next/link` component interacts with the App Router when the component containing the link is dynamically rendered (e.g., based on data fetched during rendering).  Under certain circumstances, clicking the link may not navigate as expected, leading to inconsistent behavior. This behavior is less likely in standard page-based routing.

## Reproduction Steps

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior when clicking the links.