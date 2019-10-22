Before begin you need to change `{{ INPUT_YOUR_ACCOUNT_ID }}` to you relevant account ID in `templates/ecr-policy.j2`.


Fill users in `vars/main.yml`. If user does not exist - it will be created and his access/secret keys will be stored locally.
Users can only pull images from repositories.
