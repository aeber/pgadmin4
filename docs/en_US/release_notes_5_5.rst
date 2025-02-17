************
Version 5.5
************

Release date: 2021-07-15

This release contains a number of bug fixes and new features since the release of pgAdmin4 5.4.

New features
************

| `Issue #3920 <https://redmine.postgresql.org/issues/3920>`_ -  Do not block the query editor window when running a query.

Housekeeping
************


Bug fixes
*********

| `Issue #4189 <https://redmine.postgresql.org/issues/4189>`_ -  Ensure that the Data Output panel can be snapped back after it is detached.
| `Issue #6388 <https://redmine.postgresql.org/issues/6388>`_ -  Fixed replace keyboard shortcut issue in the query tool on the normal keyboard layout.
| `Issue #6398 <https://redmine.postgresql.org/issues/6398>`_ -  Fixed an issue where detaching the query editor panel gives a blank white panel.
| `Issue #6448 <https://redmine.postgresql.org/issues/6448>`_ -  Fixed an issue in the search object when searching in 'all types' or 'subscription' if the user doesn't have access to the subscription.
| `Issue #6489 <https://redmine.postgresql.org/issues/6489>`_ -  Fixed an issue where Execute/Refresh button should not be disabled when we run the empty query.
| `Issue #6505 <https://redmine.postgresql.org/issues/6505>`_ -  Fixed an issue where the New Connection Drop Down has lost default maintenance database, auto-select, and tab-through functionality.
| `Issue #6541 <https://redmine.postgresql.org/issues/6541>`_ -  Ensure that setting 'Open in new browser tab' should be visible, it should not be based on the value of 'ENABLE_PSQL'.
| `Issue #6547 <https://redmine.postgresql.org/issues/6547>`_ -  Fixed copy/paste issues for PSQL tool terminal.
| `Issue #6555 <https://redmine.postgresql.org/issues/6555>`_ -  Fixed Czech translation string for 'Login' keyword.
