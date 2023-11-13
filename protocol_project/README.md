# Protocol Project

This is a basic Python project for a protocol with 5 phases: Setup, Registration, Voting, Tally, and Verification.

## Project Structure

The project has the following structure:

```
protocol_project
├── src
│   ├── setup.py
│   ├── registration.py
│   ├── voting.py
│   ├── tally.py
│   └── verification.py
├── tests
│   ├── test_setup.py
│   ├── test_registration.py
│   ├── test_voting.py
│   ├── test_tally.py
│   └── test_verification.py
├── .gitignore
├── setup.py
├── requirements.txt
└── README.md
```

## Setup

To set up the project, run the following command:

```
python setup.py install
```

This will install all the necessary dependencies listed in the `requirements.txt` file.

## Running the Project

To run the project, navigate to the `src` directory and run the following command:

```
python main.py
```

## Running the Tests

To run the tests, navigate to the `tests` directory and run the following command:

```
python -m unittest discover
```

## Contributing

Contributions are welcome. Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)