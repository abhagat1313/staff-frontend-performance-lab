# Staff Frontend Performance Lab

A production-style frontend performance engineering lab focused on:

- Rendering strategies
- Browser internals
- Hydration
- Core Web Vitals
- Bundle optimization
- CDN caching
- React rendering performance
- Observability
- Staff-level architectural tradeoffs

## Goals

This project intentionally builds slow and inefficient patterns first,
then progressively optimizes them while measuring real performance impact.

## Planned Topics

- CSR vs SSR vs SSG vs Edge Rendering
- Hydration analysis
- Main-thread blocking
- Core Web Vitals
- Code splitting
- Tree shaking
- Compression
- CloudFront caching
- React rendering optimization
- Observability and RUM

## Stack

Frontend:
- React
- Next.js
- TypeScript

Infra:
- Docker
- NGINX
- AWS CloudFront
- S3

Observability:
- Lighthouse
- Chrome DevTools
- React Profiler
- Web Vitals
- Dynatrace / Grafana