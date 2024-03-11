# OpenSpartan Workshop Datafile Exploration

## Pre-requisites

To analyze data in this notebook, you will need to use [OpenSpartan Workshop](https://openspartan.com/docs/workshop/guides/get-started/) to capture the [initial SQLite database](https://openspartan.com/docs/workshop/guides/understanding-the-local-database/).

Once you have the data file, you can follow the steps:

1. Make sure you have at least [Python](https://www.python.org/) 3.12 installed on your local machine.
1. Clone this repository.
1. Navigate to the `workshop-datafile` folder (the one you're in right now).
1. Create and activate a new virtual environment:
	
	Windows:

	```powershell
	python -m venv .env
	.\.env\Scripts\activate
	```

	macOS/Linux:

	```bash
	python -m venv .env
	source .env/bin/activate
	```

1. Install all required dependencies:

	```bash
	pip install -r requirements.txt
	```

1. Launch the notebook interface with `jupyter notebook`.
