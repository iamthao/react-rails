web: bundle exec thin start -p $PORT
scheduler: bundle exec clockwork app/clockwork.rb
resque_01: QUEUE=* bundle exec rake resque:work
resque_02: QUEUE=* bundle exec rake resque:work
resque_03: QUEUE=* bundle exec rake resque:work
resque_04: QUEUE=* bundle exec rake resque:work
resque_05: QUEUE=* bundle exec rake resque:work
resque_06: QUEUE=* bundle exec rake resque:work
resque_07: QUEUE=* bundle exec rake resque:work
resque_08: QUEUE=* bundle exec rake resque:work
resque_09: QUEUE=* bundle exec rake resque:work
resque_10: QUEUE=* bundle exec rake resque:work
release: bundle exec rake db:migrate

