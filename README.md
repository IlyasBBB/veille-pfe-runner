# veille-pfe-runner

Scheduled runner (GitHub Actions) for a private repository. The code, the configuration and the data live in
that private repository; this one only holds the workflow, so the passes use the free minutes that GitHub
gives public repositories. The logs here stay minimal: the details of each pass are saved in the private
repository.

Triggers: an external scheduler (workflow dispatch every 3 hours), plus a twice-daily backup schedule.
