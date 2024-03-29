# Summary
* Scheduled email sender is a solution which provides the ability to create and manage mailing lists, newsletters, automated campaigns and more.

# Configuration:
The latest configuration was created using AutoFlow version __1.0.13__
Upload the configuration to API AutoFlow.

# Video Demo for developers
[![Watch the video](https://img.youtube.com/vi/uIkiKWeU6kM/0.jpg)](https://youtu.be/uIkiKWeU6kM)

[[Watch the video]](https://youtu.be/uIkiKWeU6kM)
Open in new tab by using CTRL+click (on Windows and Linux) or CMD+click (on MacOS) on the link.


# API AutoFlow Download
Visit https://www.interactor.com/product/autoflow/download to get a free version of API AutoFlow

<!--
# User Manual
Click link to open the user manual <a href="https://www.interactor.com/autoflow/use-cases/scheduled-email-sender/" target="_blank">https://www.interactor.com/autoflow/use-cases/scheduled-email-sender/</a>
-->

# Flow overview

## [Server] Load Email List
###### Port: 1111
#### [GET] /email-list-read
Name: Email List Read
#### [POST] /email-list-load
Name: Email List Load
#### [POST] /email-list-delete
Name: Email List Delete

## [Server] Compose Email
###### Port: 1112
#### [GET] /email-content-created
Name: Edit Content
#### [POST] /schedule-email
Name: Schedule Email
#### [POST] /schedule-delete
Name: Unschedule Email

## [Server] SMTP Settings
###### Port: 1113
#### [GET] /smtp-server-get
Name: Get SMTP Server Setting
#### [POST] /smtp-server-set
Name: Set SMTP Server
#### [POST] /smtp-server-delete
Name: Delete SMTP Server Setting

## [Server] Troubleshoot
###### Port: 1114
#### [POST] /count-reset
Name: Count Reset
#### [POST] /delay-send-off
Name: Delay Send Off
#### [GET] /last-run
Name: Last Run Get
#### [POST] /last-run-set
Name: Last Run Set
#### [POST] /schedule-reset
Name: Schedule Reset
#### [POST] /scheduler-off
Name: Scheduler Off

## [Timer] Scheduler

## [Timer] Delay Send

# Need help?

<!--
Leave your comment on <a href="https://interactor.com/autoflow/use-cases/scheduled-email-sender/" target="_blank">https://interactor.com/autoflow/use-cases/scheduled-email-sender/</a>
-->

Is you have questions about this solution, feel free to post your question on the community "<a href="[https://interactor.com/autoflow/questions](https://www.interactor.com/support/forum)" target="_blank">Ask Questions</a>" website.
