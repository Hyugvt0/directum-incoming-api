# Manual Test Cases for Incoming Correspondence API

## Positive Case

- [ ] Create document with all required fields -> Expect 201 Created
- [ ] Create document without attachments -> Expect 201 Created

## Negative Cases

- [ ] Missing `subject` -> Expect 400
- [ ] Invalid `receivedDate` format -> Expect 400
- [ ] No token -> Expect 401
- [ ] Duplicate `externalId` -> Expect 409
