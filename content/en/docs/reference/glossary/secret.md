---
title: Secret
id: secret
date: 2018-04-12
full-link: /docs/concepts/configuration/secret/
tags:
- core-object
- security
short_description: >
  Stores sensitive information, such as passwords, OAuth tokens, and ssh keys.

---

Allows for more control over how sensitive information is used and reduces the risk of accidental exposure, including [encryption](https://kubernetes.io/docs/tasks/administer-cluster/encrypt-data/#ensure-all-secrets-are-encrypted) at rest.  A {{< glossary_tooltip text="Pod" term_id="pod" >}} references the secret as a file in a volume mount or by the kubelet pulling images for a pod. Secrets are great for confidential data and [ConfigMaps](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/) for non-confidential data.

