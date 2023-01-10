# Order for the logic of the this role

- [x    ] gather infromation

- [ ] if elastic pkg is installed
  - [ ] if reinstall is true
    - [ ] remove elastic pkg
    - [ ] install elastic pkg
  - [ ] if update
    - [ ] try to update verison /need to be allow in role\
- [ ] else
  - [ ] install elastic pkg

- [ ] reset server keystore
- [ ] generate config *(if no security is set xpack will be disabled)*
  - [ ] if ssl is true
    - [ ] generate ssl
    - [ ] generate ssl config
  - [ ] if auth is true
    - [ ] create user

(*todo add self logging and metrics for the role*)
