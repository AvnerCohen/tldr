# mutt

> Command-line email client.

- Open the specified mailbox:

`mutt -f {{mailbox}}`

- Send an email and specify a subject and a cc recipient:

`mutt -s {{subject}} -c {{cc@example.com}} {{recipient@example.com}}`

- Send an email with files attached:

`mutt -a {{file1}} {{file2}} -- {{recipient@example.com}}`

- Specify a file to include as the message body:

`mutt -i {{file}} {{recipient@example.com}}`

- Specify a draft file containing the header and the body of the message:

`mutt -H {{file}} {{recipient@example.com}}`