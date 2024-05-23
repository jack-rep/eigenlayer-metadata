# eigenlayer-metadata

Eigenlayer requires metadata.json and logo.png to be in public github repo and is linked to it in the operator.yml that is used in the validator to register.

logo.png must be less than 1 MB

metadata.json must comply with their rules:
https://docs.eigenlayer.xyz/eigenlayer/operator-guides/operator-installation#operator-configuration-and-registration
(specific regex for name and description, as well as less than 4KB total file size)
