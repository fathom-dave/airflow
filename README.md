# Fathom Debugging Interview

Thanks for interviewing at Fathom!

For this problem we're going to be debugging some code in an existing codebase. Feel free to look expore the code and read through the origional [README](./AIRFLOW_README.md) for a minute. We'll provide you with an insertion point for each part below.

For the purpose of this interview, we'll provide you with an insertion point for each part below. Feel free to skip around between parts if you get stuck.

This is your code base, feel free to look around, add tests and refactor any code as needed. Additionally feel free to look up any information on the internet as well. The only thing off limits is the origional codebase and bug reports for this reposiitory.

Good luck!

P.S. - The codebase already has a linter and formatter that you can invoke using make lint and make fix.


## Parts

### 1. tests/providers/ftp/hooks/test_ftp.py
Start by running:

```shell
pytest tests/providers/ftp/hooks/test_ftp.py
```

### 2. tests/cli/commands/test_kerberos_command.py

```shell
pytest tests/cli/commands/test_kerberos_command.py
```

### 3. tests/api_connexion/schemas/test_task_instance_schema.py

```shell
pytest tests/api_connexion/schemas/test_task_instance_schema.py
```

### 4. tests/models/test_dag.py

```shell
pytest tests/models/test_dag.py
```

### 5. tests/sensors/test_external_task_sensor.py

```shell
pytest tests/sensors/test_external_task_sensor.py
```