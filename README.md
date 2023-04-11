# env0-tf-testing
This branch shows the doppler testing and using Doppler for all the secrets/variable management.  This way you can keep states seperate and not have to resort to using workspaces and can still have a easy way to centrally manage the secrets and vars that TF uses.

In order for this to work you just need to setup a `doppler_token` var in the project one for dev and one for prod based on Access Tokens you setup in Doppler in dev and prd as well in the project there.  You also will need the azure creds that you have already setup in env0 to be specified in the project environments section.

![Env0 Doppler SS](env0-doppler-ss.png)