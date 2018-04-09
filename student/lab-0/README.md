# lab-0

## Setup Google Cloud

1. Notify [the instructor][instructor_email] with your Google Account email address.  This is used to provide access to the lab resources.

2. Check your email that notifies you of access, then log into https://console.cloud.google.com.

## Confirm Project Access

1. You can confirm you have access when you have logged into Google Cloud and can see the [Project info][identifying_projects] says **Project Name** of "bosh-operator-class".

2. Next, sign in to your Google Account, and click on the [SSH button][ssh-button] to connect to the **student-workspace** server.

3. Clone this repo in your home folder and update submodules:

```
$ git clone https://github.com/starkandwayne/operator-workshop.git
$ cd operator-workshop
$ git submodule update --init --recursive
```

This copies all our labs down to the **student-workspace** server.  We use a VM running on the target infrastructure because this gives us a common denominator for each of us who might be using different computer platforms to use this workshop (Windows, Mac, Linux).

[instructor_email]: <mailto:tbird@starkandwayne.com>
[identifying_projects]: https://cloud.google.com/resource-manager/docs/creating-managing-projects#identifying_projects