# dev-limits-k8s-webhook

Mutating k8s webhook which deletes resources on all created pods. Probably not the wisest thing to do, but sometimes might be helpful during local development with one-node cluster – if more than a few pods needs to be created, it might happen that resource limits will prevent that from happening, even though the pods could run just fine.
