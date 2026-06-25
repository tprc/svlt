---
title: Hello git
publishDate: 30 Nov 2021
description: Every blog starts with a single post. This is yours. Make it great.
---

To choose a specific ssh key for git command

GIT_SSH_COMMAND="ssh -i ~/.ssh/your_specific_key -o IdentitiesOnly=yes" git clone git@github.com:username/repo.git

      <dd><textarea id="ssh_key_key" class="form-control key_value form-control" placeholder="Begins with &#39;ssh-rsa&#39;, &#39;ecdsa-sha2-nistp256&#39;, &#39;ecdsa-sha2-nistp384&#39;, &#39;ecdsa-sha2-nistp521&#39;, &#39;ssh-ed25519&#39;, &#39;sk-ecdsa-sha2-nistp256@openssh.com&#39;, or &#39;sk-ssh-ed25519@openssh.com&#39;" name="ssh_key[key]">


