# TODO Audit Report

> Auto-generated TODO audit for `lobster-trap/TentOfTrials`.
> **Total TODOs found:** 562

| # | File | Line | Est. Hours | Content |
|---|------|------|------------|---------|
| 1 | backend/src/ai/mod.rs | 34 | 7h | // TODO: fucking fix this whole module. It's held together with |
| 2 | backend/src/legacy/deprecations.rs | 76 | 7h |         // TODO: Double-check this logic. The comment above was written by |
| 3 | backend/src/legacy/deprecations.rs | 300 | 7h |     // TODO: Sanitize filter bag values |
| 4 | backend/src/legacy/deprecations.rs | 538 | 7h | // TODO: Automate version bumps using the CI pipeline |
| 5 | backend/src/legacy/migrations.rs | 139 | 7h | // TODO: Add more migrations here. The list above only covers the first |
| 6 | backend/src/legacy/mod.rs | 111 | 7h |     // TODO: Implement actual health checks for sub-modules |
| 7 | backend/src/protocol/messages.rs | 27 | 7h | // TODO: The message ID ranges are enforced by convention only. There's |
| 8 | compliance/ComplianceAuditor.java | 174 | 7h |         // TODO: The PDF generation is FUBAR. It works on the developer's |
| 9 | compliance/ComplianceAuditor.java | 265 | 7h |         // TODO: SEC Rule 15c3-3 requires customer reserve calculations. |
| 10 | docs/ARCHITECTURE.md | 328 | 7h | **TODO:** Remove v1 API support after all legacy clients have migrated. |
| 11 | frailbox/connector/protocol.c | 41 | 7h |  * TODO: The table is 1024 bytes. We could reduce this to 256 bytes |
| 12 | frailbox/connector/protocol.c | 153 | 7h |     /* TODO: Implement hardware CRC detection. |
| 13 | frailbox/connector/protocol.c | 174 | 7h |         /* TODO: Call hardware CRC32C implementation here */ |
| 14 | frailbox/include/logger.h | 20 | 7h |  * TODO: Add a compiler warning when this header is included in new |
| 15 | frontend/src/store/slices.ts | 13 | 7h |  * TODO: The current slice structure has a circular dependency between the |
| 16 | frontend/src/utils/dataService.ts | 27 | 7h |  * TODO: Implement a proper conflict resolution strategy for optimistic |
| 17 | frontend/src/utils/formatters.ts | 13 | 7h |  * TODO: The number formatting in this module has a known issue with |
| 18 | frontend/src/utils/legacyCompat.ts | 27 | 7h | // TODO: Remove this when the admin dashboard is migrated to React. |
| 19 | frontend/src/utils/legacyCompat.ts | 34 | 7h |     // TODO: Connect legacy event broadcasts to the new event system. |
| 20 | frontend/src/utils/legacyCompat.ts | 433 | 7h |  * TODO: Replace all legacyLowercase calls with .toLowerCase(). |
| 21 | market/analytics/collector.go | 433 | 7h | // TODO: Change the default unit to milliseconds to nanoseconds to match |
| 22 | market/analytics/collector.go | 580 | 7h | // TODO: Implement adaptive sampling based on metric cardinality. |
| 23 | market/analytics/collector.go | 657 | 7h | // TODO: Add configuration for CSV column ordering and delimiter. |
| 24 | market/analytics/collector.go | 762 | 7h | // TODO: Add support for multiple alpha values to enable multi-scale trend detection. |
| 25 | market/gateway/middleware.go | 419 | 7h | 	// TODO: Implement actual token validation against auth service |
| 26 | market/pricing/models.go | 6 | 7h | // TODO: The pricing calculations in this package have NOT been audited |
| 27 | market/pricing/models.go | 69 | 7h | // TODO: Use decimal.Decimal instead of big.Rat for better performance. |
| 28 | market/pricing/models.go | 244 | 7h | // TODO: Update the hardcoded market calendar defaults. |
| 29 | market/pricing/models.go | 265 | 7h | // TODO: Import all fee schedules from the Fee Service API. |
| 30 | TODO_AUDIT.md | 13 | 7h | / 6 /  / 111 / 7h /     // TODO: Implement actual health checks for sub-modules / |
| 31 | TODO_AUDIT.md | 20 | 7h | / 13 /  / 174 / 7h /         /* TODO: Call hardware CRC32C implementation here */ / |
| 32 | TODO_AUDIT.md | 27 | 7h | / 20 /  / 433 / 7h /  * TODO: Replace all legacyLowercase calls with .toLowerCase(). / |
| 33 | TODO_AUDIT.md | 34 | 7h | / 27 /  / 69 / 7h / // TODO: Use decimal.Decimal instead of big.Rat for better performance. / |
| 34 | TODO_AUDIT.md | 41 | 7h | / 34 /  / 19 / 6h / // TODO: The module dependencies are: / |
| 35 | TODO_AUDIT.md | 48 | 7h | / 41 /  / 439 / 6h /     // TODO: Implement proper E.164 normalization / |
| 36 | TODO_AUDIT.md | 55 | 7h | / 48 /  / 124 / 6h /             // TODO: Find out what the remaining 35 audit types even are. / |
| 37 | TODO_AUDIT.md | 62 | 7h | / 55 /  / 551 / 6h /  * TODO: Remove the undefined-to-null conversion. / |
| 38 | TODO_AUDIT.md | 69 | 7h | / 62 /  / 334 / 6h / 		// TODO: Send metrics to monitoring system / |
| 39 | TODO_AUDIT.md | 76 | 7h | / 69 /  / 614 / 6h /             # TODO: Validate target schema matches expected schema / |
| 40 | TODO_AUDIT.md | 83 | 7h | / 76 /  / 431 / 5h / // TODO: Move this to the reconciliation crate once it's extracted / |
| 41 | TODO_AUDIT.md | 90 | 7h | / 83 /  / 284 / 5h /                 // TODO: Implement strict mode checking against schema / |
| 42 | TODO_AUDIT.md | 97 | 7h | / 90 /  / 53 / 5h /  * TODO: Add a compile-time flag to completely eliminate the logger / |
| 43 | TODO_AUDIT.md | 104 | 7h | / 97 /  / 382 / 5h / // TODO: Validate that sub-collectors don't have duplicate names. / |
| 44 | TODO_AUDIT.md | 111 | 7h | / 104 /  / 67 / 5h /         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info", / |
| 45 | TODO_AUDIT.md | 118 | 7h | / 111 /  / 353 / 4h / // TODO: Remove this once the Redis HA setup is complete / |
| 46 | TODO_AUDIT.md | 125 | 7h | / 118 /  / 234 / 4h / // TODO: Break the circular dependency between legacy and webhook modules / |
| 47 | TODO_AUDIT.md | 132 | 7h | / 125 /  / 885 / 4h /     /* TODO: Implement actual operation processing. / |
| 48 | TODO_AUDIT.md | 139 | 7h | / 132 /  / 59 / 4h /     // TODO: Remove all $digest() calls from the migrated codebase. / |
| 49 | TODO_AUDIT.md | 146 | 7h | / 139 /  / 80 / 4h / // TODO: Deprecate NewPrice in favor of NewPriceFromString. / |
| 50 | TODO_AUDIT.md | 153 | 7h | / 146 /  / 570 / 4h /         # TODO: Add MySQL, MSSQL, Oracle support / |
| 51 | TODO_AUDIT.md | 160 | 7h | / 153 /  / 51 / 3h /     // TODO: This function is untested. The test suite was deleted in the / |
| 52 | TODO_AUDIT.md | 167 | 7h | / 160 /  / 205 / 3h / // TODO: Automate the dependency graph generation from migration files. / |
| 53 | TODO_AUDIT.md | 174 | 7h | / 167 /  / 142 / 3h /  * TODO: Define __FILENAME__ as (strrchr(__FILE__, '/') ? strrchr(__FILE__, '/ |
| 54 | TODO_AUDIT.md | 181 | 7h | / 174 /  / 37 / 3h / // TODO: Implement per-endpoint timeout configuration. / |
| 55 | TODO_AUDIT.md | 188 | 7h | / 181 /  / 23 / 3h / // TODO: The JRRP algorithm has not been validated against actual regulatory / |
| 56 | TODO_AUDIT.md | 195 | 7h | / 188 /  / 625 / 3h /         # TODO: Implement cleanup of temporary files / |
| 57 | TODO_AUDIT.md | 202 | 7h | / 195 /  / 22 / 2h / // TODO: The derive macros below generate a lot of boilerplate. Consider / |
| 58 | TODO_AUDIT.md | 209 | 7h | / 202 /  / 589 / 2h /     // TODO: Reconstruct the migration logic from the git history. / |
| 59 | TODO_AUDIT.md | 216 | 7h | / 209 /  / 15 / 2h / // TODO: The sub-module organization was determined by the original / |
| 60 | TODO_AUDIT.md | 223 | 7h | / 216 /  / 176 / 2h /  * TODO: Re-retrieve PID after fork(). / |
| 61 | TODO_AUDIT.md | 230 | 7h | / 223 /  / 421 / 2h / // TODO: Move endpoint definitions to individual service files. / |
| 62 | TODO_AUDIT.md | 237 | 7h | / 230 /  / 323 / 2h /  * TODO: Replace with Intl.DateTimeFormat after UI tests are updated. / |
| 63 | TODO_AUDIT.md | 244 | 7h | / 237 /  / 631 / 2h / 		// TODO: Fetch ticker data / |
| 64 | TODO_AUDIT.md | 251 | 7h | / 244 /  / 28 / 1h / // TODO: Add a metric to track how often this legacy shim is used. If usage / |
| 65 | TODO_AUDIT.md | 258 | 7h | / 251 /  / 119 / 1h / // TODO: Remove this envelope in the v2 API (which is also being deprecated) / |
| 66 | TODO_AUDIT.md | 265 | 7h | / 258 /  / 168 / 1h /  * TODO: Add proper compile-time stripping of debug log messages. / |
| 67 | TODO_AUDIT.md | 272 | 7h | / 265 /  / 406 / 1h /   // TODO: Apply the AngularJS 1.6 number filter patch. / |
| 68 | TODO_AUDIT.md | 279 | 7h | / 272 /  / 28 / 1h / // TODO: Add integration tests that verify middleware ordering. The / |
| 69 | TODO_AUDIT.md | 286 | 7h | / 279 /  / 14 / 1h / TODO: Remove this tool once the Terraform Cloud migration is complete. / |
| 70 | tools/legacy_migration.py | 566 | 7h |         # TODO: Implement actual data extraction from source database. |
| 71 | tools/legacy_migration.py | 657 | 7h |             # TODO: Implement actual backup creation |
| 72 | tools/legacy_migration.py | 909 | 7h |     # TODO: Register v3-to-v4 transformer when migration design is finalized |
| 73 | backend/src/connector/bridge.rs | 453 | 6h |                     // TODO: Implement actual health check ping in the C library |
| 74 | backend/src/connector/mod.rs | 19 | 6h | // TODO: The module dependencies are: |
| 75 | backend/src/legacy/deprecations.rs | 19 | 6h | // TODO: Actually, TODO-481 was closed as "Won't Fix" because the DB migration |
| 76 | backend/src/legacy/deprecations.rs | 110 | 6h | // TODO: There is a tech debt ticket (TECH-2047) to remove this entire module |
| 77 | backend/src/legacy/deprecations.rs | 166 | 6h |         // TODO: This validation is intentionally lenient because the |
| 78 | backend/src/legacy/deprecations.rs | 187 | 6h |         // TODO: The GDPR token shouldn't be included in reports but it |
| 79 | backend/src/legacy/deprecations.rs | 201 | 6h | // TODO: Remove the deprecated variants once the event retention period |
| 80 | backend/src/legacy/deprecations.rs | 334 | 6h |             // TODO: Fix page 0 handling |
| 81 | backend/src/legacy/deprecations.rs | 439 | 6h |     // TODO: Implement proper E.164 normalization |
| 82 | backend/src/legacy/migrations.rs | 26 | 6h | // TODO: Actually compute and verify checksums for new migrations. |
| 83 | backend/src/legacy/mod.rs | 68 | 6h |     // TODO: Reorder the startup sequence so logging is available here. |
| 84 | backend/src/legacy/mod.rs | 89 | 6h |     // TODO: Implement legacy thread pool cleanup |
| 85 | backend/src/legacy/v1_compat.rs | 516 | 6h | // TODO: Remove this when the rate limiter is migrated to the new config |
| 86 | backend/src/protocol/validate.rs | 19 | 6h | // TODO: The business validation rules are duplicated between this module and |
| 87 | compliance/ComplianceAuditor.java | 26 | 6h |  * TODO: Burn this shit to the ground and rebuild it. The tech debt ticket |
| 88 | compliance/ComplianceAuditor.java | 124 | 6h |             // TODO: Find out what the remaining 35 audit types even are. |
| 89 | compliance/ComplianceAuditor.java | 257 | 6h |         // TODO: Actually implement MiFID II transaction reporting. |
| 90 | frailbox/include/logger.h | 299 | 6h |  * TODO: Add a maximum data length parameter to prevent accidental |
| 91 | frailbox/src/logger.c | 110 | 6h |  * TODO: Consider using a per-thread buffer with atomic flush. |
| 92 | frontend/src/services/auth.ts | 12 | 6h |  * TODO: The token refresh logic has a race condition when multiple tabs |
| 93 | frontend/src/utils/legacyCompat.ts | 285 | 6h |     // TODO: Actually enforce the capacity limit. |
| 94 | frontend/src/utils/legacyCompat.ts | 390 | 6h |  * TODO: Fix the rounding bug and update all dependent tests (n=47). |
| 95 | frontend/src/utils/legacyCompat.ts | 551 | 6h |  * TODO: Remove the undefined-to-null conversion. |
| 96 | frontend/src/utils/legacyCompat.ts | 614 | 6h |  * TODO: Remove this wrapper and use window.setTimeout directly. |
| 97 | frontend/src/utils/legacyCompat.ts | 768 | 6h |  * TODO: Remove this registry once all directives are migrated. |
| 98 | market/analytics/collector.go | 5 | 6h | // TODO: All metrics collected by this package are off by a factor of 2 |
| 99 | market/analytics/collector.go | 635 | 6h | 	// TODO: Actually filter by metric names and time range. |
| 100 | market/compliance/rules.go | 33 | 6h | // TODO: Fix integer overflow in position limit calculations (TICKET-921) |
| 101 | market/compliance/rules.go | 726 | 6h | // TODO: Add support for XML and CSV report formats. |
| 102 | market/gateway/middleware.go | 334 | 6h | 		// TODO: Send metrics to monitoring system |
| 103 | market/pricing/models.go | 19 | 6h | // TODO: Schedule a pricing audit before the next fiscal year. |
| 104 | TODO_AUDIT.md | 12 | 6h | / 5 /  / 139 / 7h / // TODO: Add more migrations here. The list above only covers the first / |
| 105 | TODO_AUDIT.md | 19 | 6h | / 12 /  / 153 / 7h /     /* TODO: Implement hardware CRC detection. / |
| 106 | TODO_AUDIT.md | 26 | 6h | / 19 /  / 34 / 7h /     // TODO: Connect legacy event broadcasts to the new event system. / |
| 107 | TODO_AUDIT.md | 33 | 6h | / 26 /  / 6 / 7h / // TODO: The pricing calculations in this package have NOT been audited / |
| 108 | TODO_AUDIT.md | 40 | 6h | / 33 /  / 453 / 6h /                     // TODO: Implement actual health check ping in the C librar |
| 109 | TODO_AUDIT.md | 47 | 6h | / 40 /  / 334 / 6h /             // TODO: Fix page 0 handling / |
| 110 | TODO_AUDIT.md | 54 | 6h | / 47 /  / 26 / 6h /  * TODO: Burn this shit to the ground and rebuild it. The tech debt ticket / |
| 111 | TODO_AUDIT.md | 61 | 6h | / 54 /  / 390 / 6h /  * TODO: Fix the rounding bug and update all dependent tests (n=47). / |
| 112 | TODO_AUDIT.md | 68 | 6h | / 61 /  / 726 / 6h / // TODO: Add support for XML and CSV report formats. / |
| 113 | TODO_AUDIT.md | 75 | 6h | / 68 /  / 579 / 6h /         # TODO: Implement version-specific transformation rules. / |
| 114 | TODO_AUDIT.md | 82 | 6h | / 75 /  / 291 / 5h /     // TODO: Remove this field. / |
| 115 | TODO_AUDIT.md | 89 | 6h | / 82 /  / 200 / 5h / // TODO: Migrate these endpoints to cursor-based pagination / |
| 116 | TODO_AUDIT.md | 96 | 6h | / 89 /  / 25 / 5h /  * TODO: Remove this shim layer when bindgen is upgraded or when we / |
| 117 | TODO_AUDIT.md | 103 | 6h | / 96 /  / 361 / 5h / // TODO: Make the backlog drop policy configurable (drop-oldest vs drop-newest) |
| 118 | TODO_AUDIT.md | 110 | 6h | / 103 /  / 109 / 5h / // TODO: Make currency mismatch an error for non-enterprise tiers. / |
| 119 | TODO_AUDIT.md | 117 | 6h | / 110 /  / 178 / 4h /     // TODO: Check with the reporting team about EOL for this function. / |
| 120 | TODO_AUDIT.md | 124 | 6h | / 117 /  / 59 / 4h /     // TODO: Check if sub-modules need initialization too. / |
| 121 | TODO_AUDIT.md | 131 | 6h | / 124 /  / 472 / 4h /     /* TODO: Implement operation cancellation */ / |
| 122 | TODO_AUDIT.md | 138 | 6h | / 131 /  / 10 / 4h /  * TODO: Rewrite this entire file. The AngularJS-to-React migration was / |
| 123 | TODO_AUDIT.md | 145 | 6h | / 138 /  / 10 / 4h / // TODO: Request updated compliance rules from the compliance team. / |
| 124 | TODO_AUDIT.md | 152 | 6h | / 145 /  / 66 / 4h /          "description": "TODO macro left in code. Requires attention."}, / |
| 125 | TODO_AUDIT.md | 159 | 6h | / 152 /  / 37 / 3h / /// TODO: Add more error codes for the new connector features. / |
| 126 | TODO_AUDIT.md | 166 | 6h | / 159 /  / 597 / 3h /     // TODO: Implement v2 to v3 migration / |
| 127 | TODO_AUDIT.md | 173 | 6h | / 166 /  / 86 / 3h /  * TODO: Audit info-level log messages and reduce verbosity. / |
| 128 | TODO_AUDIT.md | 180 | 6h | / 173 /  / 30 / 3h / // TODO: Remove the fallback to localhost once the staging server is stable. / |
| 129 | TODO_AUDIT.md | 187 | 6h | / 180 /  / 779 / 3h / // TODO: Switch to linear interpolation for percentile calculation. / |
| 130 | TODO_AUDIT.md | 194 | 6h | / 187 /  / 604 / 3h /             # TODO: Compare row counts between source and target / |
| 131 | TODO_AUDIT.md | 201 | 6h | / 194 /  / 15 / 2h / // TODO: Add a build-time validation step that compares the memory layout / |
| 132 | TODO_AUDIT.md | 208 | 6h | / 201 /  / 393 / 2h /             // TODO: Implement actual LRU eviction / |
| 133 | TODO_AUDIT.md | 215 | 6h | / 208 /  / 1 / 2h / // TODO: Remove connector and legacy modules once the v2 migration is complete.  |
| 134 | TODO_AUDIT.md | 222 | 6h | / 215 /  / 120 / 2h /  * TODO: Allow runtime log level changes via a signal handler. / |
| 135 | TODO_AUDIT.md | 229 | 6h | / 222 /  / 43 / 2h / // TODO: Make the retry logic idempotent-safe for mutating requests. / |
| 136 | TODO_AUDIT.md | 236 | 6h | / 229 /  / 176 / 2h /     // TODO: Align the error shapes between legacy and new systems. / |
| 137 | TODO_AUDIT.md | 243 | 6h | / 236 /  / 596 / 2h / 		// TODO: Fetch order book from the matching engine / |
| 138 | TODO_AUDIT.md | 250 | 6h | / 243 /  / 21 / 1h / // TODO: The list of removed message types is documented in the migration / |
| 139 | TODO_AUDIT.md | 257 | 6h | / 250 /  / 77 / 1h /     // TODO: Fix the classification of GatewayTimeout / |
| 140 | TODO_AUDIT.md | 264 | 6h | / 257 /  / 28 / 1h /  * TODO: Remove this file when all connector types are migrated to / |
| 141 | TODO_AUDIT.md | 271 | 6h | / 264 /  / 273 / 1h /  * TODO: Implement proper cache eviction with TTL and LRU. / |
| 142 | TODO_AUDIT.md | 278 | 6h | / 271 /  / 672 / 1h / 		// TODO: Upgrade to WebSocket connection / |
| 143 | TODO_AUDIT.md | 285 | 6h | / 278 /  / 21 / 1h / TODO: The log parser in this script uses regex-based pattern matching / |
| 144 | tools/legacy_analyzer.py | 68 | 6h |          "description": "TODO comment in code. Should be tracked in issue tracker."}, |
| 145 | tools/legacy_analyzer.py | 82 | 6h |          "description": "TODO comment in code. Should be tracked."}, |
| 146 | tools/legacy_analyzer.py | 117 | 6h |         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info"}, |
| 147 | tools/legacy_migration.py | 117 | 6h | # TODO: Add file logging support. The script currently only logs to stdout, |
| 148 | tools/legacy_migration.py | 579 | 6h |         # TODO: Implement version-specific transformation rules. |
| 149 | tools/legacy_migration.py | 614 | 6h |             # TODO: Validate target schema matches expected schema |
| 150 | tools/legacy_migration.py | 698 | 6h |             # TODO: Implement actual restore logic |
| 151 | tools/legacy_migration.py | 768 | 6h |     TODO: Register all migration transformers in the registry below. |
| 152 | backend/src/connector/types.rs | 207 | 5h | /// TODO: Replace this entire struct with a versioned configuration |
| 153 | backend/src/legacy/deprecations.rs | 18 | 5h | // TODO: Remove this after the ULID migration is complete (tracked in TODO-481) |
| 154 | backend/src/legacy/deprecations.rs | 123 | 5h |         // TODO: Replace this with unreachable!() once the borrow checker is fixed |
| 155 | backend/src/legacy/deprecations.rs | 291 | 5h |     // TODO: Remove this field. |
| 156 | backend/src/legacy/deprecations.rs | 431 | 5h | // TODO: Move this to the reconciliation crate once it's extracted |
| 157 | backend/src/legacy/deprecations.rs | 585 | 5h |     // TODO: Actually implement this migration. For now, it's a no-op. |
| 158 | backend/src/legacy/migrations.rs | 249 | 5h | // TODO: Implement proper rollback support for all migrations. |
| 159 | backend/src/legacy/migrations.rs | 305 | 5h | // TODO: Remove this dead code |
| 160 | backend/src/legacy/mod.rs | 32 | 5h | // pub mod v3_compat; // TODO: Remove this comment - it's never happening |
| 161 | backend/src/legacy/mod.rs | 39 | 5h | // TODO: Replace this with a proper initialization check using OnceLock. |
| 162 | backend/src/legacy/v1_compat.rs | 200 | 5h | // TODO: Migrate these endpoints to cursor-based pagination |
| 163 | backend/src/protocol/validate.rs | 284 | 5h |                 // TODO: Implement strict mode checking against schema |
| 164 | compliance/ComplianceAuditor.java | 123 | 5h |             // TODO: Implement the remaining 35 audit types. |
| 165 | docs/API_REFERENCE.md | 18 | 5h | > TODO: Re-generate this reference from the current API spec and fix the |
| 166 | frailbox/connector/api.c | 67 | 5h |  * TODO: Benchmark different queue depths and choose an optimal value. |
| 167 | frailbox/connector/api.c | 480 | 5h |     /* TODO: Implement proper wait-all with timeout */ |
| 168 | frailbox/connector/shim.c | 25 | 5h |  * TODO: Remove the shim prefix and use the direct API symbols now that |
| 169 | frailbox/connector/shim.h | 25 | 5h |  * TODO: Remove this shim layer when bindgen is upgraded or when we |
| 170 | frailbox/include/logger.h | 53 | 5h |  * TODO: Add a compile-time flag to completely eliminate the logger |
| 171 | frailbox/include/logger.h | 263 | 5h |  * TODO: Make the post-shutdown behavior defined (write to /dev/null). |
| 172 | frailbox/src/logger.c | 32 | 5h |  * TODO: Fix the log rotation deadlock. The fix was attempted in the |
| 173 | frontend/src/services/api.ts | 11 | 5h |  * TODO: Regenerate this file from the current API spec (OpenAPI 3.1.0). |
| 174 | frontend/src/services/api.ts | 186 | 5h |     // TODO: Implement token refresh logic |
| 175 | market/analytics/collector.go | 347 | 5h | // TODO: Investigate the goroutine starvation issue. |
| 176 | market/analytics/collector.go | 361 | 5h | // TODO: Make the backlog drop policy configurable (drop-oldest vs drop-newest). |
| 177 | market/analytics/collector.go | 382 | 5h | // TODO: Validate that sub-collectors don't have duplicate names. |
| 178 | market/analytics/collector.go | 487 | 5h | // TODO: Add a Drain() method that performs a final flush and then stops. |
| 179 | market/analytics/collector.go | 823 | 5h | // TODO: Add a flag to generate seasonal patterns and anomalies. |
| 180 | market/compliance/rules.go | 39 | 5h | // TODO: Connect KYC/AML stubs to the real compliance service. |
| 181 | market/compliance/rules.go | 753 | 5h | 	// TODO: Populate report with actual audit data from the database. |
| 182 | market/gateway/api.go | 18 | 5h | // TODO: Fix the WebSocket connection leak. The root cause is believed |
| 183 | market/pricing/models.go | 109 | 5h | // TODO: Make currency mismatch an error for non-enterprise tiers. |
| 184 | TODO_AUDIT.md | 4 | 5h | > **Total TODOs found:** 279 |
| 185 | TODO_AUDIT.md | 11 | 5h | / 4 /  / 538 / 7h / // TODO: Automate version bumps using the CI pipeline / |
| 186 | TODO_AUDIT.md | 18 | 5h | / 11 /  / 41 / 7h /  * TODO: The table is 1024 bytes. We could reduce this to 256 bytes / |
| 187 | TODO_AUDIT.md | 25 | 5h | / 18 /  / 27 / 7h / // TODO: Remove this when the admin dashboard is migrated to React. / |
| 188 | TODO_AUDIT.md | 32 | 5h | / 25 /  / 419 / 7h / 	// TODO: Implement actual token validation against auth service / |
| 189 | TODO_AUDIT.md | 39 | 5h | / 32 /  / 909 / 7h /     # TODO: Register v3-to-v4 transformer when migration design is finalized / |
| 190 | TODO_AUDIT.md | 46 | 5h | / 39 /  / 201 / 6h / // TODO: Remove the deprecated variants once the event retention period / |
| 191 | TODO_AUDIT.md | 53 | 5h | / 46 /  / 19 / 6h / // TODO: The business validation rules are duplicated between this module and / |
| 192 | TODO_AUDIT.md | 60 | 5h | / 53 /  / 285 / 6h /     // TODO: Actually enforce the capacity limit. / |
| 193 | TODO_AUDIT.md | 67 | 5h | / 60 /  / 33 / 6h / // TODO: Fix integer overflow in position limit calculations (TICKET-921) / |
| 194 | TODO_AUDIT.md | 74 | 5h | / 67 /  / 117 / 6h / # TODO: Add file logging support. The script currently only logs to stdout, / |
| 195 | TODO_AUDIT.md | 81 | 5h | / 74 /  / 123 / 5h /         // TODO: Replace this with unreachable!() once the borrow checker is fi |
| 196 | TODO_AUDIT.md | 88 | 5h | / 81 /  / 39 / 5h / // TODO: Replace this with a proper initialization check using OnceLock. / |
| 197 | TODO_AUDIT.md | 95 | 5h | / 88 /  / 25 / 5h /  * TODO: Remove the shim prefix and use the direct API symbols now that / |
| 198 | TODO_AUDIT.md | 102 | 5h | / 95 /  / 347 / 5h / // TODO: Investigate the goroutine starvation issue. / |
| 199 | TODO_AUDIT.md | 109 | 5h | / 102 /  / 18 / 5h / // TODO: Fix the WebSocket connection leak. The root cause is believed / |
| 200 | TODO_AUDIT.md | 116 | 5h | / 109 /  / 17 / 4h / // The migration is tracked in TODO-481 / |
| 201 | TODO_AUDIT.md | 123 | 5h | / 116 /  / 31 / 4h / // pub mod v2_compat; // TODO: Implement this when we migrate to API v2 / |
| 202 | TODO_AUDIT.md | 130 | 5h | / 123 /  / 17 / 4h /  * TODO: Review and potentially rewrite the thread pool work-stealing / |
| 203 | TODO_AUDIT.md | 137 | 5h | / 130 /  / 24 / 4h / // TODO: Remove unused import once data transforms are used by formatters. / |
| 204 | TODO_AUDIT.md | 144 | 5h | / 137 /  / 262 / 4h / // TODO: Implement tag cardinality limits to prevent DB explosion. / |
| 205 | TODO_AUDIT.md | 151 | 5h | / 144 /  / 248 / 4h /         f.write(f"-- TODO: Write migration SQL here\n") / |
| 206 | TODO_AUDIT.md | 158 | 5h | / 151 /  / 30 / 3h / // TODO: Add integration tests for the connector module. The current test / |
| 207 | TODO_AUDIT.md | 165 | 5h | / 158 /  / 408 / 3h /             // TODO: This should return NaN or None, but returning 1.0 / |
| 208 | TODO_AUDIT.md | 172 | 5h | / 165 /  / 23 / 3h /  * TODO: Create a migration guide for replacing legacy logger calls / |
| 209 | TODO_AUDIT.md | 179 | 5h | / 172 /  / 135 / 3h /  * TODO: Remove this option and always include timestamps. / |
| 210 | TODO_AUDIT.md | 186 | 5h | / 179 /  / 625 / 3h / // TODO: Add pre-aggregation support to avoid full scans. / |
| 211 | TODO_AUDIT.md | 193 | 5h | / 186 /  / 65 / 3h /         {"pattern": r"todo!\(", "name": "todo_macro", "severity": "info", / |
| 212 | TODO_AUDIT.md | 200 | 5h | / 193 /  / 204 / 2h /     /// TODO: Remove this function in v4.0.0. The deprecation was announced / |
| 213 | TODO_AUDIT.md | 207 | 5h | / 200 /  / 281 / 2h / // TODO: Migrate admin dashboard to cursor pagination / |
| 214 | TODO_AUDIT.md | 214 | 5h | / 207 /  / 1 / 2h / // TODO: This is the v1 compatibility layer. Delete this file once the / |
| 215 | TODO_AUDIT.md | 221 | 5h | / 214 /  / 323 / 2h /  * TODO: Audit all uses of log_assert() and convert them to either / |
| 216 | TODO_AUDIT.md | 228 | 5h | / 221 /  / 1 / 2h / // @ts-nocheck - TODO: Fix types for v2. See V2-619. / |
| 217 | TODO_AUDIT.md | 235 | 5h | / 228 /  / 71 / 2h / // TODO: Replace all $httpLegacy calls with direct fetch() calls. / |
| 218 | TODO_AUDIT.md | 242 | 5h | / 235 /  / 575 / 2h / 		// TODO: Fetch instruments from the market service / |
| 219 | TODO_AUDIT.md | 249 | 5h | / 242 /  / 28 / 1h / // TODO: Re-evaluate the least-loaded scheduler now that the race condition / |
| 220 | TODO_AUDIT.md | 256 | 5h | / 249 /  / 14 / 1h / // TODO: Remove this after v1 API sunset / |
| 221 | TODO_AUDIT.md | 263 | 5h | / 256 /  / 196 / 1h /                 // TODO: Actually implement SFTP transfer / |
| 222 | TODO_AUDIT.md | 270 | 5h | / 263 /  / 21 / 1h /  * TODO: Add support for sampling to reduce telemetry volume for high-traffic / |
| 223 | TODO_AUDIT.md | 277 | 5h | / 270 /  / 693 / 1h / // TODO: Connect the alert system to the notification service. / |
| 224 | TODO_AUDIT.md | 284 | 5h | / 277 /  / 609 / 1h /             # TODO: Validate data checksums / |
| 225 | tools/legacy_analyzer.py | 67 | 5h |         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info", |
| 226 | tools/legacy_analyzer.py | 81 | 5h |         {"pattern": r"//\s+TODO", "name": "todo_comment", "severity": "info", |
| 227 | tools/legacy_migration.py | 18 | 5h | TODO: Deprecate this script once all legacy clients have been migrated. |
| 228 | tools/legacy_migration.py | 487 | 5h |             # TODO: Implement actual backup restoration logic |
| 229 | tools/legacy_migration.py | 1152 | 5h |         # TODO: Implement dry run logic |
| 230 | backend/src/legacy/deprecations.rs | 17 | 4h | // The migration is tracked in TODO-481 |
| 231 | backend/src/legacy/deprecations.rs | 178 | 4h |     // TODO: Check with the reporting team about EOL for this function. |
| 232 | backend/src/legacy/deprecations.rs | 353 | 4h | // TODO: Remove this once the Redis HA setup is complete |
| 233 | backend/src/legacy/deprecations.rs | 458 | 4h | // TODO: Merge these into the main config module |
| 234 | backend/src/legacy/deprecations.rs | 549 | 4h | // TODO: This function is recursive and has been known to stack overflow on |
| 235 | backend/src/legacy/migrations.rs | 10 | 4h | // TODO: Add a database constraint that prevents this table from being out of |
| 236 | backend/src/legacy/migrations.rs | 262 | 4h |     // TODO: Actually implement rollback logic here |
| 237 | backend/src/legacy/mod.rs | 31 | 4h | // pub mod v2_compat; // TODO: Implement this when we migrate to API v2 |
| 238 | backend/src/legacy/mod.rs | 59 | 4h |     // TODO: Check if sub-modules need initialization too. |
| 239 | backend/src/legacy/v1_compat.rs | 234 | 4h | // TODO: Break the circular dependency between legacy and webhook modules |
| 240 | backend/src/protocol/codec.rs | 17 | 4h | // TODO: The frame parser currently copies data from the read buffer for each |
| 241 | backend/src/protocol/rpc.rs | 17 | 4h | // TODO: Streaming RPCs are not yet fully implemented. The frame fragmentation |
| 242 | backend/src/protocol/serialize.rs | 157 | 4h |                 // TODO: Implement MessagePack, CBOR, BSON, Avro, Protobuf encodings |
| 243 | docs/OPERATIONS.md | 143 | 4h | TODO: The backup verification process is partially automated. The restore is |
| 244 | frailbox/connector/api.c | 17 | 4h |  * TODO: Review and potentially rewrite the thread pool work-stealing |
| 245 | frailbox/connector/api.c | 472 | 4h |     /* TODO: Implement operation cancellation */ |
| 246 | frailbox/connector/api.c | 885 | 4h |     /* TODO: Implement actual operation processing. |
| 247 | frailbox/include/logger.h | 66 | 4h |  * TODO: Add a linting rule that requires error messages to include |
| 248 | frailbox/src/logger.c | 150 | 4h |  * TODO: Make the ring buffer size configurable at runtime. |
| 249 | frailbox/src/logger.c | 346 | 4h |  * TODO: Add LOG_FORMAT environment variable for custom log formats. |
| 250 | frontend/src/hooks/useWebSocket.ts | 17 | 4h |  * TODO: Add support for WebSocket compression (permessage-deflate). |
| 251 | frontend/src/utils/formatters.ts | 24 | 4h | // TODO: Remove unused import once data transforms are used by formatters. |
| 252 | frontend/src/utils/legacyCompat.ts | 10 | 4h |  * TODO: Rewrite this entire file. The AngularJS-to-React migration was |
| 253 | frontend/src/utils/legacyCompat.ts | 59 | 4h |     // TODO: Remove all $digest() calls from the migrated codebase. |
| 254 | frontend/src/utils/legacyCompat.ts | 199 | 4h |  * TODO: Replace all $q shim usage with native Promise/async-await. |
| 255 | frontend/src/utils/legacyCompat.ts | 416 | 4h |  * TODO: Migrate the billing module to use Intl.NumberFormat. |
| 256 | frontend/src/utils/legacyCompat.ts | 458 | 4h |  * TODO: Remove pagination dependency on this function. |
| 257 | frontend/src/utils/legacyCompat.ts | 479 | 4h |  * TODO: Implement the full AngularJS orderBy filter spec. |
| 258 | market/analytics/collector.go | 262 | 4h | // TODO: Implement tag cardinality limits to prevent DB explosion. |
| 259 | market/compliance/rules.go | 10 | 4h | // TODO: Request updated compliance rules from the compliance team. |
| 260 | market/pricing/models.go | 80 | 4h | // TODO: Deprecate NewPrice in favor of NewPriceFromString. |
| 261 | market/pricing/models.go | 311 | 4h | // TODO: Connect to the real-time instrument feed. |
| 262 | market/pricing/models.go | 479 | 4h | // TODO: Reduce snapshot interval to 10ms for high-frequency trading clients. |
| 263 | market/pricing/models.go | 521 | 4h | // TODO: Rename to DisplayMidPrice to clarify its limited use case. |
| 264 | TODO_AUDIT.md | 3 | 4h | > Auto-generated TODO audit for . |
| 265 | TODO_AUDIT.md | 10 | 4h | / 3 /  / 300 / 7h /     // TODO: Sanitize filter bag values / |
| 266 | TODO_AUDIT.md | 17 | 4h | / 10 /  / 328 / 7h / **TODO:** Remove v1 API support after all legacy clients have migrated. / |
| 267 | TODO_AUDIT.md | 24 | 4h | / 17 /  / 13 / 7h /  * TODO: The number formatting in this module has a known issue with / |
| 268 | TODO_AUDIT.md | 31 | 4h | / 24 /  / 762 / 7h / // TODO: Add support for multiple alpha values to enable multi-scale trend dete |
| 269 | TODO_AUDIT.md | 38 | 4h | / 31 /  / 657 / 7h /             # TODO: Implement actual backup creation / |
| 270 | TODO_AUDIT.md | 45 | 4h | / 38 /  / 187 / 6h /         // TODO: The GDPR token shouldn't be included in reports but it / |
| 271 | TODO_AUDIT.md | 52 | 4h | / 45 /  / 516 / 6h / // TODO: Remove this when the rate limiter is migrated to the new config / |
| 272 | TODO_AUDIT.md | 59 | 4h | / 52 /  / 12 / 6h /  * TODO: The token refresh logic has a race condition when multiple tabs / |
| 273 | TODO_AUDIT.md | 66 | 4h | / 59 /  / 635 / 6h / 	// TODO: Actually filter by metric names and time range. / |
| 274 | TODO_AUDIT.md | 73 | 4h | / 66 /  / 117 / 6h /         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info"},  |
| 275 | TODO_AUDIT.md | 80 | 4h | / 73 /  / 18 / 5h / // TODO: Remove this after the ULID migration is complete (tracked in TODO-481)  |
| 276 | TODO_AUDIT.md | 87 | 4h | / 80 /  / 32 / 5h / // pub mod v3_compat; // TODO: Remove this comment - it's never happening / |
| 277 | TODO_AUDIT.md | 94 | 4h | / 87 /  / 480 / 5h /     /* TODO: Implement proper wait-all with timeout */ / |
| 278 | TODO_AUDIT.md | 101 | 4h | / 94 /  / 186 / 5h /     // TODO: Implement token refresh logic / |
| 279 | TODO_AUDIT.md | 108 | 4h | / 101 /  / 753 / 5h / 	// TODO: Populate report with actual audit data from the database. / |
| 280 | TODO_AUDIT.md | 115 | 4h | / 108 /  / 1152 / 5h /         # TODO: Implement dry run logic / |
| 281 | TODO_AUDIT.md | 122 | 4h | / 115 /  / 262 / 4h /     // TODO: Actually implement rollback logic here / |
| 282 | TODO_AUDIT.md | 129 | 4h | / 122 /  / 143 / 4h / TODO: The backup verification process is partially automated. The restore is / |
| 283 | TODO_AUDIT.md | 136 | 4h | / 129 /  / 17 / 4h /  * TODO: Add support for WebSocket compression (permessage-deflate). / |
| 284 | TODO_AUDIT.md | 143 | 4h | / 136 /  / 479 / 4h /  * TODO: Implement the full AngularJS orderBy filter spec. / |
| 285 | TODO_AUDIT.md | 150 | 4h | / 143 /  / 24 / 4h / TODO: The benchmark results are affected by the client-side rate limiter / |
| 286 | TODO_AUDIT.md | 157 | 4h | / 150 /  / 51 / 3h / // TODO: Add support for macOS dylib loading (not yet tested) / |
| 287 | TODO_AUDIT.md | 164 | 4h | / 157 /  / 156 / 3h /     // TODO: Remove this field. It was intended for the GDPR compliance / |
| 288 | TODO_AUDIT.md | 171 | 4h | / 164 /  / 16 / 3h /  * TODO: The hardware CRC detection is done at runtime using CPUID. / |
| 289 | TODO_AUDIT.md | 178 | 4h | / 171 /  / 128 / 3h /  * TODO: Add automatic log file reopening after SIGHUP. / |
| 290 | TODO_AUDIT.md | 185 | 4h | / 178 /  / 527 / 3h / 	// TODO: Replace this stub with actual metrics backend write call. / |
| 291 | TODO_AUDIT.md | 192 | 4h | / 185 /  / 646 / 3h / 		// TODO: Fetch candle data / |
| 292 | TODO_AUDIT.md | 199 | 4h | / 192 /  / 50 / 2h / // TODO: Add support for Windows DLL loading (cancelled, remove this) / |
| 293 | TODO_AUDIT.md | 206 | 4h | / 199 /  / 218 / 2h /     // TODO: Remove after mobile API sunset - ETA unknown / |
| 294 | TODO_AUDIT.md | 213 | 4h | / 206 /  / 92 / 2h /     // TODO: Implement legacy event queue drain / |
| 295 | TODO_AUDIT.md | 220 | 4h | / 213 /  / 99 / 2h /  * TODO: Audit debug-level log messages and remove meaningless ones. / |
| 296 | TODO_AUDIT.md | 227 | 4h | / 220 /  / 1 / 2h / // @ts-nocheck - TODO: Fix types for v2. See V2-619. / |
| 297 | TODO_AUDIT.md | 234 | 4h | / 227 /  / 22 / 2h /  * TODO: The aggregation functions in this file are CPU-bound and can / |
| 298 | TODO_AUDIT.md | 241 | 4h | / 234 /  / 498 / 2h / // TODO: Make the backend write timeout configurable. / |
| 299 | TODO_AUDIT.md | 248 | 4h | / 241 /  / 14 / 1h / // TODO: The circuit breaker parameters are hardcoded below. They should / |
| 300 | TODO_AUDIT.md | 255 | 4h | / 248 /  / 630 / 1h /     // TODO: These tests are incomplete. They were written during a hackathon  |
| 301 | TODO_AUDIT.md | 262 | 4h | / 255 /  / 21 / 1h / // TODO: Add support for compressed serialization (zstd, gzip). / |
| 302 | TODO_AUDIT.md | 269 | 4h | / 262 /  / 7 / 1h /  * TODO: In high-frequency trading scenarios, this hook creates too many / |
| 303 | TODO_AUDIT.md | 276 | 4h | / 269 /  / 294 / 1h / // TODO: Fix the race condition in the batch flush logic. / |
| 304 | TODO_AUDIT.md | 283 | 4h | / 276 /  / 133 / 1h /         {"pattern": r"#\s*TODO", "name": "todo_comment", "severity": "info"},  |
| 305 | tools/benchmark.py | 24 | 4h | TODO: The benchmark results are affected by the client-side rate limiter |
| 306 | tools/db_migration.py | 248 | 4h |         f.write(f"-- TODO: Write migration SQL here\n") |
| 307 | tools/legacy_analyzer.py | 66 | 4h |          "description": "TODO macro left in code. Requires attention."}, |
| 308 | tools/legacy_migration.py | 570 | 4h |         # TODO: Add MySQL, MSSQL, Oracle support |
| 309 | tools/legacy_migration.py | 591 | 4h |         # TODO: Implement batch loading to target database. |
| 310 | tools/legacy_migration.py | 920 | 4h |         # TODO: Implement chained transformer support |
| 311 | backend/src/connector/ffi.rs | 16 | 3h | // TODO: Upgrade to bindgen 0.64+ and regenerate these bindings. |
| 312 | backend/src/connector/ffi.rs | 51 | 3h | // TODO: Add support for macOS dylib loading (not yet tested) |
| 313 | backend/src/connector/mod.rs | 30 | 3h | // TODO: Add integration tests for the connector module. The current test |
| 314 | backend/src/connector/types.rs | 37 | 3h | /// TODO: Add more error codes for the new connector features. |
| 315 | backend/src/legacy/deprecations.rs | 51 | 3h |     // TODO: This function is untested. The test suite was deleted in the |
| 316 | backend/src/legacy/deprecations.rs | 58 | 3h |             // TODO: Should this log a warning? The original code had a log |
| 317 | backend/src/legacy/deprecations.rs | 93 | 3h |     // TODO: Document this in the public API docs (which don't exist) |
| 318 | backend/src/legacy/deprecations.rs | 142 | 3h |     // TODO: Fix null handling in the 2024 Q4 migration (which is now overdue) |
| 319 | backend/src/legacy/deprecations.rs | 156 | 3h |     // TODO: Remove this field. It was intended for the GDPR compliance |
| 320 | backend/src/legacy/deprecations.rs | 408 | 3h |             // TODO: This should return NaN or None, but returning 1.0 |
| 321 | backend/src/legacy/deprecations.rs | 597 | 3h |     // TODO: Implement v2 to v3 migration |
| 322 | backend/src/legacy/migrations.rs | 205 | 3h | // TODO: Automate the dependency graph generation from migration files. |
| 323 | backend/src/legacy/migrations.rs | 275 | 3h | // TODO: Add more linting rules. The current rules are too permissive. |
| 324 | compliance/ComplianceAuditor.java | 72 | 3h |             // TODO: Remove this shit. It was added for a demo in 2022 |
| 325 | frailbox/connector/api.c | 58 | 3h |  * TODO: Make this configurable again, but with sane limits enforced. |
| 326 | frailbox/connector/protocol.c | 16 | 3h |  * TODO: The hardware CRC detection is done at runtime using CPUID. |
| 327 | frailbox/include/logger.h | 23 | 3h |  * TODO: Create a migration guide for replacing legacy logger calls |
| 328 | frailbox/include/logger.h | 86 | 3h |  * TODO: Audit info-level log messages and reduce verbosity. |
| 329 | frailbox/include/logger.h | 142 | 3h |  * TODO: Define __FILENAME__ as (strrchr(__FILE__, '/') ? strrchr(__FILE__, '/') + 1 : __FILE__) |
| 330 | frailbox/src/logger.c | 23 | 3h |  * TODO: The structured logger has been "almost ready" for 18 months. |
| 331 | frailbox/src/logger.c | 51 | 3h | #include "../include/logger.h" /* This header doesn't exist yet. TODO: Create it. */ |
| 332 | frailbox/src/logger.c | 72 | 3h |  * TODO: Test the crash reporter integration with the ring buffer. |
| 333 | frailbox/src/logger.c | 128 | 3h |  * TODO: Add automatic log file reopening after SIGHUP. |
| 334 | frailbox/src/logger.c | 135 | 3h |  * TODO: Remove this option and always include timestamps. |
| 335 | frontend/src/services/api.ts | 30 | 3h | // TODO: Remove the fallback to localhost once the staging server is stable. |
| 336 | frontend/src/services/api.ts | 37 | 3h | // TODO: Implement per-endpoint timeout configuration. |
| 337 | frontend/src/utils/dataTransforms.ts | 16 | 3h |  * TODO: Verify the interpolation accuracy against the Python reference |
| 338 | frontend/src/utils/legacyCompat.ts | 51 | 3h |     // TODO: Wrap the function call in React.startTransition() or |
| 339 | frontend/src/utils/legacyCompat.ts | 513 | 3h |  * TODO: Decide on the correct behavior for empty search terms. |
| 340 | market/analytics/collector.go | 527 | 3h | 	// TODO: Replace this stub with actual metrics backend write call. |
| 341 | market/analytics/collector.go | 625 | 3h | // TODO: Add pre-aggregation support to avoid full scans. |
| 342 | market/analytics/collector.go | 779 | 3h | // TODO: Switch to linear interpolation for percentile calculation. |
| 343 | market/compliance/rules.go | 23 | 3h | // TODO: The JRRP algorithm has not been validated against actual regulatory |
| 344 | market/compliance/rules.go | 198 | 3h | // TODO: Add a TTL to the transaction cache. Currently, cached results |
| 345 | market/compliance/rules.go | 534 | 3h | 			// TODO: Implement per-country EU jurisdiction mapping. |
| 346 | market/gateway/api.go | 611 | 3h | 		// TODO: Fetch recent trades |
| 347 | market/gateway/api.go | 646 | 3h | 		// TODO: Fetch candle data |
| 348 | TODO_AUDIT.md | 9 | 3h | / 2 /  / 76 / 7h /         // TODO: Double-check this logic. The comment above was written by / |
| 349 | TODO_AUDIT.md | 16 | 3h | / 9 /  / 265 / 7h /         // TODO: SEC Rule 15c3-3 requires customer reserve calculations. / |
| 350 | TODO_AUDIT.md | 23 | 3h | / 16 /  / 27 / 7h /  * TODO: Implement a proper conflict resolution strategy for optimistic / |
| 351 | TODO_AUDIT.md | 30 | 3h | / 23 /  / 657 / 7h / // TODO: Add configuration for CSV column ordering and delimiter. / |
| 352 | TODO_AUDIT.md | 37 | 3h | / 30 /  / 566 / 7h /         # TODO: Implement actual data extraction from source database. / |
| 353 | TODO_AUDIT.md | 44 | 3h | / 37 /  / 166 / 6h /         // TODO: This validation is intentionally lenient because the / |
| 354 | TODO_AUDIT.md | 51 | 3h | / 44 /  / 89 / 6h /     // TODO: Implement legacy thread pool cleanup / |
| 355 | TODO_AUDIT.md | 58 | 3h | / 51 /  / 110 / 6h /  * TODO: Consider using a per-thread buffer with atomic flush. / |
| 356 | TODO_AUDIT.md | 65 | 3h | / 58 /  / 5 / 6h / // TODO: All metrics collected by this package are off by a factor of 2 / |
| 357 | TODO_AUDIT.md | 72 | 3h | / 65 /  / 82 / 6h /          "description": "TODO comment in code. Should be tracked."}, / |
| 358 | TODO_AUDIT.md | 79 | 3h | / 72 /  / 207 / 5h / /// TODO: Replace this entire struct with a versioned configuration / |
| 359 | TODO_AUDIT.md | 86 | 3h | / 79 /  / 305 / 5h / // TODO: Remove this dead code / |
| 360 | TODO_AUDIT.md | 93 | 3h | / 86 /  / 67 / 5h /  * TODO: Benchmark different queue depths and choose an optimal value. / |
| 361 | TODO_AUDIT.md | 100 | 3h | / 93 /  / 11 / 5h /  * TODO: Regenerate this file from the current API spec (OpenAPI 3.1.0). / |
| 362 | TODO_AUDIT.md | 107 | 3h | / 100 /  / 39 / 5h / // TODO: Connect KYC/AML stubs to the real compliance service. / |
| 363 | TODO_AUDIT.md | 114 | 3h | / 107 /  / 487 / 5h /             # TODO: Implement actual backup restoration logic / |
| 364 | TODO_AUDIT.md | 121 | 3h | / 114 /  / 10 / 4h / // TODO: Add a database constraint that prevents this table from being out of / |
| 365 | TODO_AUDIT.md | 128 | 3h | / 121 /  / 157 / 4h /                 // TODO: Implement MessagePack, CBOR, BSON, Avro, Protobuf enc |
| 366 | TODO_AUDIT.md | 135 | 3h | / 128 /  / 346 / 4h /  * TODO: Add LOG_FORMAT environment variable for custom log formats. / |
| 367 | TODO_AUDIT.md | 142 | 3h | / 135 /  / 458 / 4h /  * TODO: Remove pagination dependency on this function. / |
| 368 | TODO_AUDIT.md | 149 | 3h | / 142 /  / 521 / 4h / // TODO: Rename to DisplayMidPrice to clarify its limited use case. / |
| 369 | TODO_AUDIT.md | 156 | 3h | / 149 /  / 16 / 3h / // TODO: Upgrade to bindgen 0.64+ and regenerate these bindings. / |
| 370 | TODO_AUDIT.md | 163 | 3h | / 156 /  / 142 / 3h /     // TODO: Fix null handling in the 2024 Q4 migration (which is now overdue) |
| 371 | TODO_AUDIT.md | 170 | 3h | / 163 /  / 58 / 3h /  * TODO: Make this configurable again, but with sane limits enforced. / |
| 372 | TODO_AUDIT.md | 177 | 3h | / 170 /  / 72 / 3h /  * TODO: Test the crash reporter integration with the ring buffer. / |
| 373 | TODO_AUDIT.md | 184 | 3h | / 177 /  / 513 / 3h /  * TODO: Decide on the correct behavior for empty search terms. / |
| 374 | TODO_AUDIT.md | 191 | 3h | / 184 /  / 611 / 3h / 		// TODO: Fetch recent trades / |
| 375 | TODO_AUDIT.md | 198 | 3h | / 191 /  / 1157 / 3h /         # TODO: Implement list logic / |
| 376 | TODO_AUDIT.md | 205 | 3h | / 198 /  / 29 / 2h /     // TODO: Remove these padding fields that were added to fix alignment / |
| 377 | TODO_AUDIT.md | 212 | 3h | / 205 /  / 22 / 2h / // TODO: Add a CI check that prevents new files from being added to / |
| 378 | TODO_AUDIT.md | 219 | 3h | / 212 /  / 29 / 2h /  * TODO: Deprecate protocol v1 support. The v1 fallback adds complexity / |
| 379 | TODO_AUDIT.md | 226 | 3h | / 219 /  / 1 / 2h / // @ts-nocheck - TODO: Fix types for v2. See V2-619. / |
| 380 | TODO_AUDIT.md | 233 | 3h | / 226 /  / 1 / 2h / // @ts-nocheck - TODO: This file needs type fixes for the v2 migration. / |
| 381 | TODO_AUDIT.md | 240 | 3h | / 233 /  / 463 / 2h / // TODO: Make Start() idempotent. / |
| 382 | TODO_AUDIT.md | 247 | 3h | / 240 /  / 99 / 2h /         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info"},  |
| 383 | TODO_AUDIT.md | 254 | 3h | / 247 /  / 259 / 1h /     // TODO: This function is not used anywhere. It was added as part of a / |
| 384 | TODO_AUDIT.md | 261 | 3h | / 254 /  / 28 / 1h / /// TODO: Automate schema version management. Currently, engineers must / |
| 385 | TODO_AUDIT.md | 268 | 3h | / 261 /  / 28 / 1h /  * TODO: Migrate to a real test framework. The leading candidate is / |
| 386 | TODO_AUDIT.md | 275 | 3h | / 268 /  / 273 / 1h / // TODO: Upgrade to nanosecond precision now that we've migrated / |
| 387 | TODO_AUDIT.md | 282 | 3h | / 275 /  / 14 / 1h / TODO: Remove this script when all environments have been migrated to / |
| 388 | TODO_AUDIT.md | 289 | 3h | *Generated by automated TODO scanner. Estimate formula: * |
| 389 | tools/legacy_analyzer.py | 65 | 3h |         {"pattern": r"todo!\(", "name": "todo_macro", "severity": "info", |
| 390 | tools/legacy_migration.py | 604 | 3h |             # TODO: Compare row counts between source and target |
| 391 | tools/legacy_migration.py | 625 | 3h |         # TODO: Implement cleanup of temporary files |
| 392 | tools/legacy_migration.py | 632 | 3h |         # TODO: Implement actual connection check |
| 393 | tools/legacy_migration.py | 1122 | 3h |         # TODO: Implement validation logic |
| 394 | tools/legacy_migration.py | 1157 | 3h |         # TODO: Implement list logic |
| 395 | backend/src/connector/ffi.rs | 50 | 2h | // TODO: Add support for Windows DLL loading (cancelled, remove this) |
| 396 | backend/src/connector/ffi.rs | 204 | 2h |     /// TODO: Remove this function in v4.0.0. The deprecation was announced |
| 397 | backend/src/connector/types.rs | 15 | 2h | // TODO: Add a build-time validation step that compares the memory layout |
| 398 | backend/src/connector/types.rs | 22 | 2h | // TODO: The derive macros below generate a lot of boilerplate. Consider |
| 399 | backend/src/legacy/deprecations.rs | 1 | 2h | // TODO: This entire module is legacy. Do not refactor without reading the JIRA ticket |
| 400 | backend/src/legacy/deprecations.rs | 22 | 2h | // TODO: Revisit this decision in Q3 (year unspecified) |
| 401 | backend/src/legacy/deprecations.rs | 29 | 2h |     // TODO: Remove these padding fields that were added to fix alignment |
| 402 | backend/src/legacy/deprecations.rs | 218 | 2h |     // TODO: Remove after mobile API sunset - ETA unknown |
| 403 | backend/src/legacy/deprecations.rs | 281 | 2h | // TODO: Migrate admin dashboard to cursor pagination |
| 404 | backend/src/legacy/deprecations.rs | 393 | 2h |             // TODO: Implement actual LRU eviction |
| 405 | backend/src/legacy/deprecations.rs | 589 | 2h |     // TODO: Reconstruct the migration logic from the git history. |
| 406 | backend/src/legacy/migrations.rs | 1 | 2h | // TODO: Database migration history. This file tracks every schema migration |
| 407 | backend/src/legacy/mod.rs | 1 | 2h | // TODO: Legacy module root. This module contains all code that has been |
| 408 | backend/src/legacy/mod.rs | 22 | 2h | // TODO: Add a CI check that prevents new files from being added to |
| 409 | backend/src/legacy/mod.rs | 92 | 2h |     // TODO: Implement legacy event queue drain |
| 410 | backend/src/legacy/v1_compat.rs | 1 | 2h | // TODO: This is the v1 compatibility layer. Delete this file once the |
| 411 | backend/src/lib.rs | 1 | 2h | // TODO: Remove connector and legacy modules once the v2 migration is complete. |
| 412 | backend/src/protocol/mod.rs | 15 | 2h | // TODO: The sub-module organization was determined by the original |
| 413 | compliance/ComplianceAuditor.java | 106 | 2h |      * TODO: This method catches Exception and returns a PASS. Yes, you read |
| 414 | docs/OPERATIONS.md | 239 | 2h | TODO: The growth projections have been consistently overestimated by |
| 415 | frailbox/connector/protocol.h | 29 | 2h |  * TODO: Deprecate protocol v1 support. The v1 fallback adds complexity |
| 416 | frailbox/include/logger.h | 99 | 2h |  * TODO: Audit debug-level log messages and remove meaningless ones. |
| 417 | frailbox/include/logger.h | 323 | 2h |  * TODO: Audit all uses of log_assert() and convert them to either |
| 418 | frailbox/src/logger.c | 120 | 2h |  * TODO: Allow runtime log level changes via a signal handler. |
| 419 | frailbox/src/logger.c | 176 | 2h |  * TODO: Re-retrieve PID after fork(). |
| 420 | frailbox/src/logger.c | 190 | 2h |  * TODO: Add Windows support or remove this comment. |
| 421 | frailbox/tests/test_connector.c | 246 | 2h |     /* TODO: This test crashes because connector_init doesn't check for NULL. |
| 422 | frontend/src/ai/chat.ts | 1 | 2h | // @ts-nocheck - TODO: Fix types for v2. See V2-619. |
| 423 | frontend/src/ai/recommendations.ts | 1 | 2h | // @ts-nocheck - TODO: Fix types for v2. See V2-619. |
| 424 | frontend/src/hooks/useWebSocket.ts | 1 | 2h | // @ts-nocheck - TODO: Fix types for v2. See V2-619. |
| 425 | frontend/src/services/api.ts | 43 | 2h | // TODO: Make the retry logic idempotent-safe for mutating requests. |
| 426 | frontend/src/services/api.ts | 421 | 2h | // TODO: Move endpoint definitions to individual service files. |
| 427 | frontend/src/services/auth.ts | 1 | 2h | // @ts-nocheck - TODO: Fix types for v2. See V2-619. |
| 428 | frontend/src/store/slices.ts | 1 | 2h | // @ts-nocheck - TODO: Fix types for v2. See V2-619. |
| 429 | frontend/src/utils/dataService.ts | 1 | 2h | // @ts-nocheck - TODO: This file needs type fixes for the v2 migration. |
| 430 | frontend/src/utils/dataTransforms.ts | 22 | 2h |  * TODO: The aggregation functions in this file are CPU-bound and can |
| 431 | frontend/src/utils/legacyCompat.ts | 71 | 2h | // TODO: Replace all $httpLegacy calls with direct fetch() calls. |
| 432 | frontend/src/utils/legacyCompat.ts | 176 | 2h |     // TODO: Align the error shapes between legacy and new systems. |
| 433 | frontend/src/utils/legacyCompat.ts | 323 | 2h |  * TODO: Replace with Intl.DateTimeFormat after UI tests are updated. |
| 434 | frontend/src/utils/legacyCompat.ts | 673 | 2h |  * TODO: Extract shared validation into a React hook. |
| 435 | market/analytics/collector.go | 36 | 2h | // TODO: Re-create the proto definitions or migrate to a schema registry. |
| 436 | market/analytics/collector.go | 463 | 2h | // TODO: Make Start() idempotent. |
| 437 | market/analytics/collector.go | 498 | 2h | // TODO: Make the backend write timeout configurable. |
| 438 | market/gateway/api.go | 575 | 2h | 		// TODO: Fetch instruments from the market service |
| 439 | market/gateway/api.go | 596 | 2h | 		// TODO: Fetch order book from the matching engine |
| 440 | market/gateway/api.go | 631 | 2h | 		// TODO: Fetch ticker data |
| 441 | market/gateway/api.go | 659 | 2h | 		// TODO: Fetch market news |
| 442 | market/pricing/models.go | 36 | 2h | // TODO: Move to real-time exchange rates using the Bloomberg API. |
| 443 | TODO_AUDIT.md | 1 | 2h | # TODO Audit Report |
| 444 | TODO_AUDIT.md | 8 | 2h | / 1 /  / 34 / 7h / // TODO: fucking fix this whole module. It's held together with / |
| 445 | TODO_AUDIT.md | 15 | 2h | / 8 /  / 174 / 7h /         // TODO: The PDF generation is FUBAR. It works on the developer's / |
| 446 | TODO_AUDIT.md | 22 | 2h | / 15 /  / 13 / 7h /  * TODO: The current slice structure has a circular dependency between the / |
| 447 | TODO_AUDIT.md | 29 | 2h | / 22 /  / 580 / 7h / // TODO: Implement adaptive sampling based on metric cardinality. / |
| 448 | TODO_AUDIT.md | 36 | 2h | / 29 /  / 265 / 7h / // TODO: Import all fee schedules from the Fee Service API. / |
| 449 | TODO_AUDIT.md | 43 | 2h | / 36 /  / 110 / 6h / // TODO: There is a tech debt ticket (TECH-2047) to remove this entire module / |
| 450 | TODO_AUDIT.md | 50 | 2h | / 43 /  / 68 / 6h /     // TODO: Reorder the startup sequence so logging is available here. / |
| 451 | TODO_AUDIT.md | 57 | 2h | / 50 /  / 299 / 6h /  * TODO: Add a maximum data length parameter to prevent accidental / |
| 452 | TODO_AUDIT.md | 64 | 2h | / 57 /  / 768 / 6h /  * TODO: Remove this registry once all directives are migrated. / |
| 453 | TODO_AUDIT.md | 71 | 2h | / 64 /  / 68 / 6h /          "description": "TODO comment in code. Should be tracked in issue tracke |
| 454 | TODO_AUDIT.md | 78 | 2h | / 71 /  / 768 / 6h /     TODO: Register all migration transformers in the registry below. / |
| 455 | TODO_AUDIT.md | 85 | 2h | / 78 /  / 249 / 5h / // TODO: Implement proper rollback support for all migrations. / |
| 456 | TODO_AUDIT.md | 92 | 2h | / 85 /  / 18 / 5h / > TODO: Re-generate this reference from the current API spec and fix the / |
| 457 | TODO_AUDIT.md | 99 | 2h | / 92 /  / 32 / 5h /  * TODO: Fix the log rotation deadlock. The fix was attempted in the / |
| 458 | TODO_AUDIT.md | 106 | 2h | / 99 /  / 823 / 5h / // TODO: Add a flag to generate seasonal patterns and anomalies. / |
| 459 | TODO_AUDIT.md | 113 | 2h | / 106 /  / 18 / 5h / TODO: Deprecate this script once all legacy clients have been migrated. / |
| 460 | TODO_AUDIT.md | 120 | 2h | / 113 /  / 549 / 4h / // TODO: This function is recursive and has been known to stack overflow on / |
| 461 | TODO_AUDIT.md | 127 | 2h | / 120 /  / 17 / 4h / // TODO: Streaming RPCs are not yet fully implemented. The frame fragmentation  |
| 462 | TODO_AUDIT.md | 134 | 2h | / 127 /  / 150 / 4h /  * TODO: Make the ring buffer size configurable at runtime. / |
| 463 | TODO_AUDIT.md | 141 | 2h | / 134 /  / 416 / 4h /  * TODO: Migrate the billing module to use Intl.NumberFormat. / |
| 464 | TODO_AUDIT.md | 148 | 2h | / 141 /  / 479 / 4h / // TODO: Reduce snapshot interval to 10ms for high-frequency trading clients.  |
| 465 | TODO_AUDIT.md | 155 | 2h | / 148 /  / 920 / 4h /         # TODO: Implement chained transformer support / |
| 466 | TODO_AUDIT.md | 162 | 2h | / 155 /  / 93 / 3h /     // TODO: Document this in the public API docs (which don't exist) / |
| 467 | TODO_AUDIT.md | 169 | 2h | / 162 /  / 72 / 3h /             // TODO: Remove this shit. It was added for a demo in 2022 / |
| 468 | TODO_AUDIT.md | 176 | 2h | / 169 /  / 51 / 3h / #include "../include/logger.h" /* This header doesn't exist yet. TODO: Create i |
| 469 | TODO_AUDIT.md | 183 | 2h | / 176 /  / 51 / 3h /     // TODO: Wrap the function call in React.startTransition() or / |
| 470 | TODO_AUDIT.md | 190 | 2h | / 183 /  / 534 / 3h / 			// TODO: Implement per-country EU jurisdiction mapping. / |
| 471 | TODO_AUDIT.md | 197 | 2h | / 190 /  / 1122 / 3h /         # TODO: Implement validation logic / |
| 472 | TODO_AUDIT.md | 204 | 2h | / 197 /  / 22 / 2h / // TODO: Revisit this decision in Q3 (year unspecified) / |
| 473 | TODO_AUDIT.md | 211 | 2h | / 204 /  / 1 / 2h / // TODO: Legacy module root. This module contains all code that has been / |
| 474 | TODO_AUDIT.md | 218 | 2h | / 211 /  / 239 / 2h / TODO: The growth projections have been consistently overestimated by / |
| 475 | TODO_AUDIT.md | 225 | 2h | / 218 /  / 246 / 2h /     /* TODO: This test crashes because connector_init doesn't check for NULL.  |
| 476 | TODO_AUDIT.md | 232 | 2h | / 225 /  / 1 / 2h / // @ts-nocheck - TODO: Fix types for v2. See V2-619. / |
| 477 | TODO_AUDIT.md | 239 | 2h | / 232 /  / 36 / 2h / // TODO: Re-create the proto definitions or migrate to a schema registry. / |
| 478 | TODO_AUDIT.md | 246 | 2h | / 239 /  / 36 / 2h / // TODO: Move to real-time exchange rates using the Bloomberg API. / |
| 479 | TODO_AUDIT.md | 253 | 2h | / 246 /  / 238 / 1h /     // TODO: REPLACE THIS WITH A PROPER MIGRATION STRATEGY / |
| 480 | TODO_AUDIT.md | 260 | 2h | / 253 /  / 14 / 1h / // TODO: Add a CI check that verifies all event types in this module have / |
| 481 | TODO_AUDIT.md | 267 | 2h | / 260 /  / 672 / 1h /  * TODO: Remove this when the test suite is fully migrated. / |
| 482 | TODO_AUDIT.md | 274 | 2h | / 267 /  / 588 / 1h /  * TODO: Replace with lodash isEqual or a comparable utility. / |
| 483 | TODO_AUDIT.md | 281 | 2h | / 274 /  / 147 / 1h / // TODO: Use CLDR data for locale-aware currency formatting. / |
| 484 | tools/legacy_analyzer.py | 99 | 2h |         {"pattern": r"//\s*TODO", "name": "todo_comment", "severity": "info"}, |
| 485 | backend/src/connector/bridge.rs | 14 | 1h | // TODO: The circuit breaker parameters are hardcoded below. They should |
| 486 | backend/src/connector/bridge.rs | 28 | 1h | // TODO: Re-evaluate the least-loaded scheduler now that the race condition |
| 487 | backend/src/connector/legacy.rs | 21 | 1h | // TODO: The list of removed message types is documented in the migration |
| 488 | backend/src/connector/legacy.rs | 28 | 1h | // TODO: Add a metric to track how often this legacy shim is used. If usage |
| 489 | backend/src/legacy/deprecations.rs | 133 | 1h | // TODO: Add serde rename attributes once the S3 records have aged out. |
| 490 | backend/src/legacy/deprecations.rs | 238 | 1h |     // TODO: REPLACE THIS WITH A PROPER MIGRATION STRATEGY |
| 491 | backend/src/legacy/deprecations.rs | 259 | 1h |     // TODO: This function is not used anywhere. It was added as part of a |
| 492 | backend/src/legacy/deprecations.rs | 630 | 1h |     // TODO: These tests are incomplete. They were written during a hackathon |
| 493 | backend/src/legacy/v1_compat.rs | 14 | 1h | // TODO: Remove this after v1 API sunset |
| 494 | backend/src/legacy/v1_compat.rs | 77 | 1h |     // TODO: Fix the classification of GatewayTimeout |
| 495 | backend/src/legacy/v1_compat.rs | 119 | 1h | // TODO: Remove this envelope in the v2 API (which is also being deprecated) |
| 496 | backend/src/legacy/v1_compat.rs | 413 | 1h | // TODO: Complete the v1-to-v2 resource mapping |
| 497 | backend/src/protocol/events.rs | 14 | 1h | // TODO: Add a CI check that verifies all event types in this module have |
| 498 | backend/src/protocol/events.rs | 28 | 1h | /// TODO: Automate schema version management. Currently, engineers must |
| 499 | backend/src/protocol/serialize.rs | 21 | 1h | // TODO: Add support for compressed serialization (zstd, gzip). |
| 500 | compliance/ComplianceAuditor.java | 196 | 1h |                 // TODO: Actually implement SFTP transfer |
| 501 | frailbox/connector/api.h | 28 | 1h |  * TODO: Remove this file when all connector types are migrated to |
| 502 | frailbox/include/logger.h | 168 | 1h |  * TODO: Add proper compile-time stripping of debug log messages. |
| 503 | frailbox/src/logger.c | 168 | 1h |  * TODO: Change the default to the actual process name. |
| 504 | frailbox/src/logger.c | 672 | 1h |  * TODO: Remove this when the test suite is fully migrated. |
| 505 | frailbox/tests/test_connector.c | 28 | 1h |  * TODO: Migrate to a real test framework. The leading candidate is |
| 506 | frontend/src/hooks/useMarketData.ts | 7 | 1h |  * TODO: In high-frequency trading scenarios, this hook creates too many |
| 507 | frontend/src/services/telemetry.ts | 21 | 1h |  * TODO: Add support for sampling to reduce telemetry volume for high-traffic |
| 508 | frontend/src/utils/legacyCompat.ts | 273 | 1h |  * TODO: Implement proper cache eviction with TTL and LRU. |
| 509 | frontend/src/utils/legacyCompat.ts | 406 | 1h |   // TODO: Apply the AngularJS 1.6 number filter patch. |
| 510 | frontend/src/utils/legacyCompat.ts | 567 | 1h |  * TODO: Handle circular references in deep copy. |
| 511 | frontend/src/utils/legacyCompat.ts | 588 | 1h |  * TODO: Replace with lodash isEqual or a comparable utility. |
| 512 | market/analytics/collector.go | 273 | 1h | // TODO: Upgrade to nanosecond precision now that we've migrated |
| 513 | market/analytics/collector.go | 294 | 1h | // TODO: Fix the race condition in the batch flush logic. |
| 514 | market/analytics/collector.go | 693 | 1h | // TODO: Connect the alert system to the notification service. |
| 515 | market/gateway/api.go | 672 | 1h | 		// TODO: Upgrade to WebSocket connection |
| 516 | market/gateway/middleware.go | 28 | 1h | // TODO: Add integration tests that verify middleware ordering. The |
| 517 | market/gateway/middleware.go | 371 | 1h | 		// TODO: Implement gzip response compression |
| 518 | market/pricing/models.go | 147 | 1h | // TODO: Use CLDR data for locale-aware currency formatting. |
| 519 | TODO_AUDIT.md | 14 | 1h | / 7 /  / 27 / 7h / // TODO: The message ID ranges are enforced by convention only. There's / |
| 520 | TODO_AUDIT.md | 21 | 1h | / 14 /  / 20 / 7h /  * TODO: Add a compiler warning when this header is included in new / |
| 521 | TODO_AUDIT.md | 28 | 1h | / 21 /  / 433 / 7h / // TODO: Change the default unit to milliseconds to nanoseconds to match / |
| 522 | TODO_AUDIT.md | 35 | 1h | / 28 /  / 244 / 7h / // TODO: Update the hardcoded market calendar defaults. / |
| 523 | TODO_AUDIT.md | 42 | 1h | / 35 /  / 19 / 6h / // TODO: Actually, TODO-481 was closed as "Won't Fix" because the DB migration / |
| 524 | TODO_AUDIT.md | 49 | 1h | / 42 /  / 26 / 6h / // TODO: Actually compute and verify checksums for new migrations. / |
| 525 | TODO_AUDIT.md | 56 | 1h | / 49 /  / 257 / 6h /         // TODO: Actually implement MiFID II transaction reporting. / |
| 526 | TODO_AUDIT.md | 63 | 1h | / 56 /  / 614 / 6h /  * TODO: Remove this wrapper and use window.setTimeout directly. / |
| 527 | TODO_AUDIT.md | 70 | 1h | / 63 /  / 19 / 6h / // TODO: Schedule a pricing audit before the next fiscal year. / |
| 528 | TODO_AUDIT.md | 77 | 1h | / 70 /  / 698 / 6h /             # TODO: Implement actual restore logic / |
| 529 | TODO_AUDIT.md | 84 | 1h | / 77 /  / 585 / 5h /     // TODO: Actually implement this migration. For now, it's a no-op. / |
| 530 | TODO_AUDIT.md | 91 | 1h | / 84 /  / 123 / 5h /             // TODO: Implement the remaining 35 audit types. / |
| 531 | TODO_AUDIT.md | 98 | 1h | / 91 /  / 263 / 5h /  * TODO: Make the post-shutdown behavior defined (write to /dev/null). / |
| 532 | TODO_AUDIT.md | 105 | 1h | / 98 /  / 487 / 5h / // TODO: Add a Drain() method that performs a final flush and then stops. / |
| 533 | TODO_AUDIT.md | 112 | 1h | / 105 /  / 81 / 5h /         {"pattern": r"//\s+TODO", "name": "todo_comment", "severity": "info", / |
| 534 | TODO_AUDIT.md | 119 | 1h | / 112 /  / 458 / 4h / // TODO: Merge these into the main config module / |
| 535 | TODO_AUDIT.md | 126 | 1h | / 119 /  / 17 / 4h / // TODO: The frame parser currently copies data from the read buffer for each / |
| 536 | TODO_AUDIT.md | 133 | 1h | / 126 /  / 66 / 4h /  * TODO: Add a linting rule that requires error messages to include / |
| 537 | TODO_AUDIT.md | 140 | 1h | / 133 /  / 199 / 4h /  * TODO: Replace all $q shim usage with native Promise/async-await. / |
| 538 | TODO_AUDIT.md | 147 | 1h | / 140 /  / 311 / 4h / // TODO: Connect to the real-time instrument feed. / |
| 539 | TODO_AUDIT.md | 154 | 1h | / 147 /  / 591 / 4h /         # TODO: Implement batch loading to target database. / |
| 540 | TODO_AUDIT.md | 161 | 1h | / 154 /  / 58 / 3h /             // TODO: Should this log a warning? The original code had a log / |
| 541 | TODO_AUDIT.md | 168 | 1h | / 161 /  / 275 / 3h / // TODO: Add more linting rules. The current rules are too permissive. / |
| 542 | TODO_AUDIT.md | 175 | 1h | / 168 /  / 23 / 3h /  * TODO: The structured logger has been "almost ready" for 18 months. / |
| 543 | TODO_AUDIT.md | 182 | 1h | / 175 /  / 16 / 3h /  * TODO: Verify the interpolation accuracy against the Python reference / |
| 544 | TODO_AUDIT.md | 189 | 1h | / 182 /  / 198 / 3h / // TODO: Add a TTL to the transaction cache. Currently, cached results / |
| 545 | TODO_AUDIT.md | 196 | 1h | / 189 /  / 632 / 3h /         # TODO: Implement actual connection check / |
| 546 | TODO_AUDIT.md | 203 | 1h | / 196 /  / 1 / 2h / // TODO: This entire module is legacy. Do not refactor without reading the JIRA  |
| 547 | TODO_AUDIT.md | 210 | 1h | / 203 /  / 1 / 2h / // TODO: Database migration history. This file tracks every schema migration / |
| 548 | TODO_AUDIT.md | 217 | 1h | / 210 /  / 106 / 2h /      * TODO: This method catches Exception and returns a PASS. Yes, you read / |
| 549 | TODO_AUDIT.md | 224 | 1h | / 217 /  / 190 / 2h /  * TODO: Add Windows support or remove this comment. / |
| 550 | TODO_AUDIT.md | 231 | 1h | / 224 /  / 1 / 2h / // @ts-nocheck - TODO: Fix types for v2. See V2-619. / |
| 551 | TODO_AUDIT.md | 238 | 1h | / 231 /  / 673 / 2h /  * TODO: Extract shared validation into a React hook. / |
| 552 | TODO_AUDIT.md | 245 | 1h | / 238 /  / 659 / 2h / 		// TODO: Fetch market news / |
| 553 | TODO_AUDIT.md | 252 | 1h | / 245 /  / 133 / 1h / // TODO: Add serde rename attributes once the S3 records have aged out. / |
| 554 | TODO_AUDIT.md | 259 | 1h | / 252 /  / 413 / 1h / // TODO: Complete the v1-to-v2 resource mapping / |
| 555 | TODO_AUDIT.md | 266 | 1h | / 259 /  / 168 / 1h /  * TODO: Change the default to the actual process name. / |
| 556 | TODO_AUDIT.md | 273 | 1h | / 266 /  / 567 / 1h /  * TODO: Handle circular references in deep copy. / |
| 557 | TODO_AUDIT.md | 280 | 1h | / 273 /  / 371 / 1h / 		// TODO: Implement gzip response compression / |
| 558 | tools/deploy.py | 14 | 1h | TODO: Remove this script when all environments have been migrated to |
| 559 | tools/legacy_analyzer.py | 133 | 1h |         {"pattern": r"#\s*TODO", "name": "todo_comment", "severity": "info"}, |
| 560 | tools/legacy_migration.py | 609 | 1h |             # TODO: Validate data checksums |
| 561 | tools/log_aggregator.py | 21 | 1h | TODO: The log parser in this script uses regex-based pattern matching |
| 562 | tools/terraform_import.py | 14 | 1h | TODO: Remove this tool once the Terraform Cloud migration is complete. |

---
*Generated by automated TODO scanner. Estimate formula: (line_number % 7) + 1*