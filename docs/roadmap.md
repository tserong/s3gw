<!-- markdownlint-disable MD024 -->

# Roadmap

## 2022

### Quarter 1

- Brainstorm process

---

### Quarter 2

- Initial project setup
- First tests with RGW
- [UI mockups][1]

---

### Quarter 3

- File-based backend
- Basic S3 operations support
- User management
- Helm charts
- Testing
- UI implementation
- Documentation
- Basic object management & versioning
- Bucket management
- Automation implementation

---

### Quarter 4

- Object deletion/undeletion
- Multipart uploads
- Multipart copy
- ACL support
- UI: Basic object explorer
- Rancher Partner chart

## 2023

### Plan of record

Features the team is committed to deliver within the timeframe.

#### Quarter 1

- [Expiration Lifecycle Management (unversioned)][2]
- [Object locks][3]
- [Object listing with prefixes/filters][4]
- [Telemetry][5]
- [UI: Object deletion/undeletion][7]

---

#### Quarter 2

- [Expiration Lifecycle Management (versioned)][8]
- [Access & Identity Management][10]
- [Metrics from backend][9]
- [UI: Object versioning][11]

---

#### Quarter 3

- [Implement Amazon Security Token][12]

---

#### Quarter 4

- [Metrics on UI][15]

---

### Plan of direction

Features the team wants to develop but are currently not a top priority.

- [Cross-site replication][13]
- [Implement Storage classes][14]
- [CRD based configuration of buckets and rbac][6]

### In scope

Features that aren't currently planned but the project would accept external
contributions.

- [SSO][16]

### Out of scope

Features that aren't being considered unless core assumptions change.

!!! Info
    Please note that this roadmap is an evergreen document and will most
    certainly evolve as we continue to learn from our users.

[1]: https://www.figma.com/file/qGWXKomwzIUhsDz7QqixAc/S3-Wireframe---Branded?t=PAXtYcfL0tEPLPmm-1
[2]: https://github.com/aquarist-labs/s3gw/issues/215
[3]: https://github.com/aquarist-labs/s3gw/issues/228
[4]: https://github.com/aquarist-labs/s3gw/issues/256
[5]: https://github.com/aquarist-labs/s3gw/issues/202
[6]: https://github.com/aquarist-labs/s3gw/issues/76
[7]: https://github.com/aquarist-labs/s3gw/issues/255
[8]: https://github.com/aquarist-labs/s3gw/issues/257
[9]: https://github.com/aquarist-labs/s3gw/issues/258
[10]: https://github.com/aquarist-labs/s3gw/issues/227
[11]: https://github.com/aquarist-labs/s3gw/issues/271
[12]: https://github.com/aquarist-labs/s3gw/issues/229
[13]: https://github.com/aquarist-labs/s3gw/issues/259
[14]: https://github.com/aquarist-labs/s3gw/issues/230
[15]: https://github.com/aquarist-labs/s3gw/issues/258
[16]: https://github.com/aquarist-labs/s3gw/issues/260
