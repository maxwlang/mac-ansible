1. Install ansible
- `python3 -m pip install --user pipx`
- `~/Library/Python/3.9/bin/pipx ensurepath`
- `exit`
- `pipx install ansible-core`

2. Configure
Change settings in settings.yml, provide sudo password.

3. Run playbook
`ansible-playbook --connection=local playbook.yml`
