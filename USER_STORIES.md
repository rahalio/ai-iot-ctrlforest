# CtrlForest — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### SOC analyst

- As a SOC analyst, I want alerts with attack class and contributing features, so I can triage without opening a research notebook.
- As a SOC analyst, I want to mark false positives, so the next weighted forest training down-weights those patterns.
- As a SOC analyst, I want FPR and recall dashboards by class, so I know whether Probe coverage improved after re-selection.

### SDN controller engineer

- As a controller engineer, I want detection overhead metrics, so I can refuse a model that starves forwarding.
- As a controller engineer, I want quarantine actions behind a policy flag, so research accuracy never becomes an accidental outage.

### IoT platform owner

- As a platform owner, I want novel-attack recall compared to our signature box, so I can justify retiring overlapping rules.

### Compliance auditor

- As an auditor, I want an immutable log of mitigations and model versions, so automated drops are reviewable.
- As an auditor, I want feature-set freezes documented, so we know what the model was allowed to see.

### Security administrator

- As a security admin, I want to schedule Bat feature re-selection after a major device onboarding wave, so drift does not silently degrade detection.
- As a security admin, I want rollback to the prior forest when FPR breaches the ceiling for 24 hours, so analysts are not flooded.
