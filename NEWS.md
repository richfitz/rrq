# rrq 0.2.1

* Add support for within-task progress updates, using the `rrq::rrq_task_progress_update` function, which can be called from any task run from `rrq` and queried with `$task_progress` from a `rrq_controller` (mrc-600)

# rrq 0.2.0

* Rewrite of the package to simplify queue creation and dependency chain (mrc-538 / #9, mrc-519 / #8, mrc-472 / #7)