# Accessing watsonx Assistant via API


## Overview

This page will demonstrate how to access watsonx Assistant via an API call.

### Resources
  - [watsonx Assistant v2](https://cloud.ibm.com/apidocs/assistant-v2)


## High level steps:

1. Access watsonx Assistant from Resource List in the IBM Cloud Account
2. Get API Key for watsonx Assistant from Launch webpage
3. Get Serice Instance URL from Launch webpage
4. Get Assistant ID from webpage within the Assistant settings
5. Copy the Skill ID from the watsonx Assistant settings
6. Obtain the Session ID from CLI CURL

```{}
{ curl -X POST -u "apikey:{apikey}" "{url}/v2/assistants/{environment_id}/sessions?version=2021-11-27" }
curl -X POST -u "apikey:APIKEY" "URL"
{
"session_id":"SESSION_ID"
}
```
7. dsgsd
9. 
