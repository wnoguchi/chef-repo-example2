# Vagrant and Berkshelf example

Vagrant and Berkshelf example.  
This is toy repository.

## Install

* Install vagrant plugins.

```bash
vagrant plugin install vagrant-omnibus
vagrant plugin install vagrant-berkshelf
```

* Install Berkshelf gem.

```bash
cat <<EOF >>Gemfile
gem 'berkshelf'
EOF

bundle install
```

* Berkshelf initialize.

```bash
mkdir vagrant1
cd vagrant1/
bundle exec berks init
```

## References

- [Ruby - 今っぽい Vagrant + Chef Solo チュートリアル - Qiita [キータ]](http://qiita.com/taiki45/items/b46a2f32248720ec2bae)
