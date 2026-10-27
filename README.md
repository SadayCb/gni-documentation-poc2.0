# GNI Software — LOAN_API Documentation

## General

| Field | Value |
|---|---|
| Document Name | LOAN_API Technical & Business Reference |
| Created Date | 2026-10-27 |
| Created By | Documentation PoC |
| Version | 0.2 — Draft |
| Language | English |
| Classification | Internal review / Not approved for external distribution |

## Introduction

### Purpose of This Document

Introduce the cross-module loan operations package `LOAN_API`, its public interface, implementation-derived behavior and operational dependencies. It is **not** tied to APEX page 2201.

### Scope of This Document

- **88 public declarations** from the supplied package specification, including **4 overloaded names**.
- Technical signatures, business-purpose summaries, input and output parameters, observed SQL dependencies and operational notes.
- Source-derived insights requiring review by a developer before client-facing publication.

## API Specifications

- [Complete public API reference](docs/api/loan-api.md)
- [Review and approval checklist](docs/review-notes.md)

## Data Model

The full schema definition is outside the supplied package source. Database object references are listed within each routine's section; they do not substitute for verified table DDL or ER diagrams.

## Error Handling

Per-method observed error messages are documented in the API reference. Error contracts, transaction boundaries and raised-message handlers must be confirmed during technical review.

## Navigation

Use the functional-category index at the beginning of [the API reference](docs/api/loan-api.md); every link targets one unique method or overload.
