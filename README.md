
# Insta Bot v2

This Python script serves as an Instagram Uploading Bot that takes YouTube short links and uploads them to an Instagram account with media.

## Features

- Automatically fetches YouTube short links.
- Downloads the corresponding media.
- Uploads the media to the specified Instagram account.

## Prerequisites

- Python 3.6 or later
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/milliyin/insta-bot.git
    cd insta-bot
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Configure the bot:

    - Update the `config.py` file with your Instagram credentials and any other necessary settings.

## Configuration

Open `config.py` and set the following parameters:

- `username`: Your Instagram username.
- `password`: Your Instagram password.
- `upload_text`: Your Post Caption

Example `config.py`:

```python
username = 'your_username'
password = 'your_password'
upload_text = "Caption Text"
```

## Usage

Run the bot by executing `main.py`:

```bash
python main.py
```

The script will:

1. Fetch the YouTube short links specified in `config.py`.
2. Download the corresponding media.
3. Upload the media to your Instagram account.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/fooBar`).
3. Commit your changes (`git commit -am 'Add some fooBar'`).
4. Push to the branch (`git push origin feature/fooBar`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [InstaPy](https://github.com/timgrossmann/InstaPy) for inspiration.
- [pytube](https://github.com/pytube/pytube) for YouTube media downloading.

## Contact

For any inquiries or support, please open an issue in the GitHub repository.
