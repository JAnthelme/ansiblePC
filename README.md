# ansiblePC
Standard Linux PC Provisionning

todo 
- timeshift / clonezilla
- sandboxes
- virtualbox / QEMU
- openvpn
- etcher vs ubsimager
- thunderbird
- bleachbit

## Ansible:
### Structure:
- `local.yml` in the ansible folder e.g. `~/andiblePC/`
- then `packages.yml` in `~/andiblePC/tasks/`

### Pulling:
-   Github > AnsiblePC repo > Code > copy Clone with HTTPS (e.g. `https://github.com/FooBar/ansiblePC.git`)
-   go to ansible directory and then `sudo ansible-pull -U https://github.com/JAnthelme/ansiblePC.git`
-   `apt update...`
-   `sudo cp -a /media/sf_SHARED/. ~/.ssh/win`
-    `vim ~/.ssh/config`
      - `IdentityFile ~/.ssh/id_rsa`
      - `IdentityFile ~/.ssh/win/id_rsa`
- `chmod 400 ./win/id_rsa`
- ssh R1 > pf > vp exp > visco bundle > import saved vp > nam+pw...

## Misc:
-[Ansible Gotchas](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html#gotchas)

-[YAML escape chars](https://yaml.org/spec/1.2.2/#57-escaped-characters)


