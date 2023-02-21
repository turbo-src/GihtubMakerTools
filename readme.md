# Gihtub Maker Tools

## Usage

### Create a repo.

```
python main.py -c -r testrepo
```

With docker.

```
docker run -it \
gihtub-maker-tools \
-c -r testrepo
```

### Delete a repo.

```
python main.py -d -r testrepo
```

With docker.

```
docker run -it \
gihtub-maker-tools \
-d -r testrepo
```

## Setup

Clone this repository.

`git clone https://github.com/bedardn93/GihtubMakerTools`

Create a `ght.ini` file with you info inside `GihtubMakerTools`.

```
[github.org]
User = bedardn93
Token = ghp_abcdefg
Organization =
```

You'll generate api token from Github. You need the scopes `repo` and `delete_repo`

Install everything.

```
pip install -r requirements.txt.
```

Or if using docker.

```
docker build -t gihtub-maker-tools .
```

Everytime you update your token, you'll need to rebuild the image if using docker.
