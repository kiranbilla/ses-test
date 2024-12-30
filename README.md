# SES Test Sample Code

This is a sample code for SES Test.

## Installation

1. Clone the repository

```bash
git clone https://github.com/kiranbilla/ses-test
```

2. Virtual Environment

```bash
cd ses-test
virtualenv .venv
source .venv/bin/activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

## Usage

First, edit env file with your ses credentials go to ses service in aws console form there should be create a ses Access key ID,Secret access key only
```bash
cp env.example .env
```

Then, run the following command to send email
```bash
python send_email.py
```
