# LOAN_API — Reviewer Checklist

- [ ] Confirm business-purpose descriptions for all public methods.
- [ ] Validate overloaded method signatures and usage scenarios.
- [ ] Verify data model: referenced tables, synonyms, views and account mappings.
- [ ] Check `DBMS_SQL` query execution and dynamic UPDATE composition for security and proper value escaping.
- [ ] Verify EOD/SOD operation controls, transaction commit/rollback ownership, restart and concurrency rules.
- [ ] Confirm errors raised by `r(...)`, `PLOG.ASSERT#`, and delegated packages.
- [ ] Validate interest day-count, grace, penalty and schedule cases with approved business tests.
- [ ] Review method-level examples in a test environment before publishing executable calls.
- [ ] Review customer-facing content separately to avoid disclosure of internal implementation and controls.

**Important:** Automated extraction of direct SQL dependencies is heuristic. It can miss dynamic SQL and delegated calls; it can also include dependencies in nested implementation code. All dependency claims require validation prior to external publication.
