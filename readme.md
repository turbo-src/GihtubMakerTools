# Github Maker Tools

## Usage

### Create a repo.

```
python main.py -c -r testrepo
```

With docker.

```
docker run -it \
github-maker-tools \
-c -r testrepo
```

### Delete a repo.

```
python main.py -d -r testrepo
-c -r testrepo
```

With docker.

```
docker run -it \
github-maker-tools \
-d -r testrepo
```

## Setup

Clone this repository.

`git clone https://github.com/bedardn93/GihtubMakerTools`

Create a `ght.ini` file with you info inside `GithubMakerTools`.

```
[github.org]
User = bedardn93
Token = ghp_abcdefg
Organization = supertestorg123
```

Install everything.

```
pip install -r /path/to/requirements.txt.
```

Or if using docker.

```
docker build -t github-maker-tools .
```