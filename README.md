# ConfluentKafkaExercise

Distributed real-time stream processing exercises with Confluent Kafka

---

## 1. Create a New Repository on the Command Line

```sh
echo "# ConfluentKafkaExercise" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yashish/ConfluentKafkaExercise.git
git push -u origin main
```

---

## 2. Push an Existing Repository from the Command Line

```sh
git remote add origin https://github.com/yashish/ConfluentKafkaExercise.git
git branch -M main
git push -u origin main
```

---

## 3. Clone in Desktop Using HTTPS

```sh
git clone https://github.com/yashish/ConfluentKafkaExercise.git
```

## 4. After creating and running a cluster in Confluent Cloud, set up the Confluent CLI to administer it.

On Mac: run brew install confluentinc/tap/cli.

On Windows or Linux: follow the instructions provided here.

1. Install / Update the Confluent CLI
Run this command to install the Confluent CLI:

```sh
curl -sL --http1.1 https://cnfl.io/cli | sh -s -- latest
```

This script will install the CLI in ./bin by default. If you want to install it somewhere else, add the path to the end of the command and to your $PATH variable.
Note: On Windows, you might need to install an appropriate Linux environment to have the curl and sh commands available, such as the Windows Subsystem for Linux (https://learn.microsoft.com/en-us/windows/wsl/about). You can also download and install the raw binaries (https://docs.confluent.io/confluent-cli/current/install.html?ajs_aid=fc86e58d-54cb-498b-91d4-3fb2b73e7232&ajs_uid=6377318#tarball-or-zip-installation)

Documentation: https://docs.confluent.io/confluent-cli/4.35/install.html

If already installed, update to the latest version with:

```sh
confluent update
```

