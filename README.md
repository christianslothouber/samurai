# Samurai

Samurai is a simple —not powerful, just simple— password generation tool designed to create secure, pronounceable passwords that are easy to remember, easy to type, and hard to crack. With Samurai, you can balance security and usability effortlessly.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/christianslothouber/samurai.git
    ```

2. Navigate to the project directory:
    ```bash
    cd samurai
    ```

3. Make the script executable:
    ```bash
      chmod +x samurai
    ```

4. (Optional) Add the directory to your `PATH` for easy access

## Usage

Once installed, you can run Samurai directly from the terminal:

```bash
samurai [options]
```

### Options

| Option | Description                                 |
|--------|---------------------------------------------|
| `-l`   | Length of the password (default: 10).       |
| `-d`   | Amount of digits used (default: 3).         |
| `-x`   | Amount of passwords generated (default: 5). |
| `-h`   | Display help and usage information.         |


### Example Commands


```bash
samurai
```

Generates the default 5 passwords. All passwords are capitalized, are 10 characters long, contain 3 digits and a special character:


```
Senoja&201
Fovoji!730
Jikeyo#063
Zeyiqe%440
Divibi#598
```

---

```bash
samurai -l 12 -d 4 -x 10
```

Generates 10 passwords. All passwords are still capitalized and contain a special character but are now 12 characters long and contain 4 digits:


```
Dolines#2745
Sadihup#1224
Javisim#5110
Wacavuh#6025
Curiqob%3863
Qafigoy%2092
Geduzen!7937
Rejifew#6983
Yilixof#0398
```

## License

This project is licensed under the [MIT License](LICENSE).
