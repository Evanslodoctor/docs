---
title: Connecting to GitHub with SSH
intro: 'You can connect to {% data variables.product.product_name %} using the Secure Shell Protocol (SSH), which provides a secure channel over an unsecured network.'
redirect_from:
  - /key-setup-redirect
  - /linux-key-setup
  - /mac-key-setup
  - /msysgit-key-setup
  - /articles/ssh-key-setup
  - /articles/generating-ssh-keys
  - /articles/generating-an-ssh-key
  - /articles/connecting-to-github-with-ssh
  - /github/authenticating-to-github/connecting-to-github-with-ssh
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - SSH
children:
  - /about-ssh
  - /using-ssh-agent-forwarding
  - /managing-deploy-keys
  - /checking-for-existing-ssh-keys
  - /generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
  - /adding-a-new-ssh-key-to-your-github-account
  - /testing-your-ssh-connection
  - /working-with-ssh-key-passphrases
shortTitle: Connect with SSH
---
## Troubleshooting

### SSH Key Permissions Issue

If you are facing issues with SSH key permissions, follow these steps:

1. **Check SSH Key Permissions:**
   Ensure that your SSH private key (`id_rsa`) has the correct permissions. Run the following command:

   ```bash
   chmod 600 ~/.ssh/id_rsa
---
