# audit

Install, configure, start, enable, add rules and configure GRUB to start audit.

## Variables

| name                 | type | default | description                      |
| -------------------- | ---- | ------- | -------------------------------- |
| `grub_backlog_limit` | int  | `8192`  |                                  |
| `uid_min`            | int  | `1000`  | Same value present in login.defs |
