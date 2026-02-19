# Bootstraping a python project

### Step 1: Initialize `uv`

Initialize the project using  [[ML - uv]]:
```bash
uv init
```

This will generate a `uv.toml` file, where we can manage the project settings and dependencies.

#### Step 2: Adding dependencies

Open the `uv.toml` file and add the dependencies (e.g. `numpy` and `pandas`)

```toml
[project]
name = "my_project"
version = "0.1.0"

[dependencies]
numpy = "*"
pandas = "*"
```

#### Step 3: Install dependencies with `uv`

```bash
uv install
```

This will create a virtual environment (if not already done) and install `numpy` and `pandas`

#### Step 4: Create a `justfile` to automate tasks
We'll create a `justfile` so we can use [[ML - just]] to define and run tasks to run the python script:

```justfile
run:
	uv run python3 script.py
```

This `justfile` recipe will run `script.py` using `uv`. More tasks can be added later, like running tests or automating data processing.


#### Step 5: Run the project
After creating the script, it can be run using `just`:
```bash
just run
```
