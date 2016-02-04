# IMAP library

### TODO

- [x] A continuation chunked parser
- [x] Way simpler output types
- [x] Output with ListT (support streaming)
- [x] A testing framework
- [ ] Support moar commands
  - [ ] All the little commands
    - [x] SELECT
    - [x] EXAMINE
    - [ ] CREATE
    - [ ] DELETE
    - [ ] RENAME
    - [ ] SUBSCRIBE
    - [ ] UNSUBSCRIBE
    - [ ] LIST
    - [ ] LSUB
    - [ ] STATUS
    - [ ] APPEND
    - [ ] CHECK
    - [ ] CLOSE
    - [ ] EXPUNGE
  - [ ] Search
  - [ ] Fetch
  - [ ] Rest
    - [ ] STARTTLS
    - [ ] AUTHENTICATE
    - [ ] BYE at any time
- [x] Ability to disconnect (support bye)
- [ ] Connection timeout
- [ ] Enable configuration when connecting
- [ ] Keep the connection alive
- [ ] React to exceptions
