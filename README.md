```
Step intall pre-commit
	1. install python from "Microft Store" ver 3.12
	2. Open cmd path {path-project-pre-commit}
		- pip install pre-commit
		- pre-commit --help
		- pre-commit install

Edit file "{path-project-pre-commit}/.git/hooks/pre-commit"
	--config="{path-project-pre-commit}\.pre-commit-config.yaml"
Config hooksPath
	git config core.hooksPath "{path-project-pre-commit}/.git/hooks"

Create file "credentials" isnot exist in C:\Users\{user.domain}\.aws
	[commit-test]
	aws_access_key_id = AKIA1111111111111111
	aws_secret_access_key = 1111111111111111111111111111111111111111
```
