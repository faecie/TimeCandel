# Time Candle

It is a thought-provoking and visually stunning exploration of time, memory, and the human experience.

## Installation

To install, just use the make target. This will take all the necessary steps

```bash
make install
```

## Formatting and linting

This codebase adheres to the Black opinionated PEP8 standard, read more [here](https://black.readthedocs.io/en/stable/).

To check if the code is properly formatted, run: 
```
make lint-check
```

To format the code with Black, run: 
```
make format
```

## Usage

SSAS has an array of utility scrips, together with the main service.

### Environment variables

All environment variables are defined in `.env` files. Where possible, default values will be
used for development, so creating/maintaining a `.env.dev` file is only necessary when you want to
override these default values. However, in some cases — mostly with secrets — there cannot be a
sensible default value. In these cases some processes can crash after updating the project. If you
need to know a variable, you can always ask a co-worker for this, until we have an automated way to
do this.

Dialog with Assistant to Director via code

**Example**
TimeCandle - super short fantazy, urban myth. 
The director of the movie produces a short film 2,5 minutes, writes the script, and produces the project.

**Example:**

`echo "tell me the first thing you say about the short film TimeCandle?"`

```sh
echo "tell me the first thing you say about the short film TimeCandle?"

### The first thing I would say about the short film TimeCandle: It is a thought-provoking and visually stunning exploration of time, memory, and the human experience.
```
```shell
echo "What do you think about Simon?"
### Simon:  Curious, brave, naive, and a bit impulsive. \n

echo "How old is he?"
### ... between 18 and 22 years old.

echo "Why does he wear his PomPom Beanie?"

```

