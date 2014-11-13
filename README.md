# Jenkins-Android

This will be an attempt to puppetize a jenkins instance for Android.

Initial setup taken from [here](http://pivotallabs.com/spinning-useful-vms-quickly-vagrant-puppet-puppet-forge/).

## Usage

Assuming you have Vagrant and Bundler already installed:

1. Clone the repo: ```git clone https://github.com/jbrunton/jenkins-android.git```.
2. Install the ruby dependencies with ```bundle install```.
3. Install the puppet dependencies with ```librarian-puppet install```.
4. Run locally with ```vagrant up```.

Jenkins should then be running at [http://localhost:8042/](http://localhost:8042/.).
