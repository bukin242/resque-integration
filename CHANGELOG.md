
#### [Current]
 * 2014-12-15 [0bdc244](../../commit/0bdc244) - __(bibendi)__ update apress-gems to 0.2.0
 * 2014-12-15 [afa473a](../../commit/afa473a) - __(bibendi)__ remove resque-rails

#### v1.0.1
 * 2014-11-28 [3362b5e](../../commit/3362b5e) - __(bibendi)__ Release 1.0.1
 * 2014-11-19 [4713fb2](../../commit/4713fb2) - __(bibendi)__ fix(hooks): verify connections for rails 4x

#### v1.0.0
 * 2014-11-13 [66329ba](../../commit/66329ba) - __(bibendi)__ Release 1.0.0
 * 2014-11-10 [78ffdd9](../../commit/78ffdd9) - __(bibendi)__ add scheduler, retry, multy-job-forks
 * 2014-10-23 [217ab60](../../commit/217ab60) - __(bibendi)__ bump version to 0.4.4
 * 2014-10-23 [ad37905](../../commit/ad37905) - __(bibendi)__ connect to redis if has credentials in config file
 * 2014-04-07 [3f05f83](../../commit/3f05f83) - __(Merkushin)__ bump version to 0.4.3
 * 2014-04-07 [9d07f2e](../../commit/9d07f2e) - __(Merkushin)__ fix(tasks): rotation now depends on environment
 * 2014-04-04 [1888006](../../commit/1888006) - __(Merkushin)__ bump version to 0.4.2
 * 2014-04-04 [e698b35](../../commit/e698b35) - __(Merkushin)__ update gem god to 0.13.4
 * 2014-04-03 [22650e0](../../commit/22650e0) - __(Merkushin)__ bump version to 0.4.1
 * 2014-04-03 [42709d7](../../commit/42709d7) - __(Merkushin)__ fix lookup for Rails const
 * 2014-04-01 [d4edc0c](../../commit/d4edc0c) - __(Merkushin)__ bump version to 0.4.0
 * 2014-04-01 [929e7dc](../../commit/929e7dc) - __(Merkushin)__ отвязка god от релизных папок
 * 2014-01-09 [fb69813](../../commit/fb69813) - __(Merkushin)__ Version bump to 0.3.1
 * 2014-01-09 [dd8679c](../../commit/dd8679c) - __(Merkushin)__ rake task for logs rotation
 * 2013-12-18 [6126234](../../commit/6126234) - __(Merkushin)__ Version bump to 0.3.0
 * 2013-12-18 [16ad62b](../../commit/16ad62b) - __(Merkushin)__ feature(logs): logs rotation
 * 2013-12-12 [32a345d](../../commit/32a345d) - __(Merkushin)__ Version bump to 0.2.11
 * 2013-12-12 [22a4912](../../commit/22a4912) - __(Merkushin)__ fix(god) fast restart with nowait При рестарте не выключаем и включаем god, а подсовываем ему новую конфигу. Теперь при смене конфига больше нет необходимости дожидаться, пока длинные джобы будут завершены и только потом будут (пере)запущены очереди. Есть небольшой минус, глобальные опции, такие как pid_file_directory не будут перечитаны.
 * 2013-12-12 [fb9a497](../../commit/fb9a497) - __(Merkushin)__ chore(git) ignore .idea
 * 2013-09-03 [f9f5d9c](../../commit/f9f5d9c) - __(Alexei Mikhailov)__ Version bump to 0.2.10
 * 2013-09-03 [6cc57ab](../../commit/6cc57ab) - __(Merkushin)__ feature(hooks): reformat process name
 * 2013-09-03 [27feb40](../../commit/27feb40) - __(Меркушин Михаил)__ feature(hooks): детальное название процесса
 * 2013-08-29 [15849c7](../../commit/15849c7) - __(Alexei Mikhailov)__ Version bump to 0.2.9
 * 2013-08-29 [da53254](../../commit/da53254) - __(Alexei Mikhailov)__ Explicitly set BUNDLE_GEMFILE for each worker
 * 2013-07-03 [e4e8432](../../commit/e4e8432) - __(Alexei Mikhailov)__ Bump to version 0.2.8
 * 2013-07-03 [87b113a](../../commit/87b113a) - __(Alexei Mikhailov)__ fix(resque-status): fix multi_json error when it choses ok_json adapter
 * 2013-06-19 [4995e5f](../../commit/4995e5f) - __(Alexei Mikhailov)__ Version bump to 0.2.7
 * 2013-06-19 [9561852](../../commit/9561852) - __(Alexei Mikhailov)__ fix(continuous): keep meta_id unchanged between continuous jobs
 * 2013-06-18 [58a67d8](../../commit/58a67d8) - __(Alexei Mikhailov)__ Version bump to 0.2.6
 * 2013-06-18 [c729cd5](../../commit/c729cd5) - __(Alexei Mikhailov)__ Freeze resque at 1.23.0
 * 2013-06-18 [a8623c3](../../commit/a8623c3) - __(Alexei Mikhailov)__ Version bump to 0.2.5
 * 2013-06-18 [9e2c065](../../commit/9e2c065) - __(Alexei Mikhailov)__ Remove resque-multi-job-forks due to bugs
 * 2013-06-18 [1a71f34](../../commit/1a71f34) - __(Alexei Mikhailov)__ More precise lock key generation
 * 2013-06-18 [3b41525](../../commit/3b41525) - __(Alexei Mikhailov)__ Fixed #33. rake resque:start теперь запускает resque при запущенном god
 * 2013-06-17 [dd4c579](../../commit/dd4c579) - __(Alexei Mikhailov)__ Fixed #34. Workaround for capistrano deploys.
 * 2013-05-22 [89da883](../../commit/89da883) - __(Alexei Mikhailov)__ Version bump to 0.2.4
 * 2013-05-22 [414e467](../../commit/414e467) - __(Alexei Mikhailov)__ Generate lock_id from hash
 * 2013-04-30 [c9507c5](../../commit/c9507c5) - __(Alexei Mikhailov)__ Version bump to 0.2.3
 * 2013-04-30 [00afd0c](../../commit/00afd0c) - __(Alexei Mikhailov)__ Auto-generated config is not changed between releases
 * 2013-04-29 [9d37c1d](../../commit/9d37c1d) - __(Alexei Mikhailov)__ Version bump to 0.2.2
 * 2013-04-29 [a90f674](../../commit/a90f674) - __(Alexei Mikhailov)__ Fixed #29: Turn off Sinatra logging
 * 2013-04-27 [8236ce5](../../commit/8236ce5) - __(Alexei Mikhailov)__ Version bump to 0.2.1
 * 2013-04-27 [2904387](../../commit/2904387) - __(Alexei Mikhailov)__ Backport hooks behaviour from 1.24.1
 * 2013-04-18 [99ed575](../../commit/99ed575) - __(Alexei Mikhailov)__ Version bump to 0.2.0
 * 2013-04-18 [caafd08](../../commit/caafd08) - __(Alexei Mikhailov)__ Fixed #15; Fixed #16; God integration
 * 2013-04-12 [ea17a78](../../commit/ea17a78) - __(Alexei Mikhailov)__ Fixed #14: log errors date/time
 * 2013-04-12 [6adff6e](../../commit/6adff6e) - __(Alexei Mikhailov)__ Fixed broken resque-status
 * 2013-04-11 [7781357](../../commit/7781357) - __(Alexei Mikhailov)__ Bump version to 0.1.6
 * 2013-04-11 [089df13](../../commit/089df13) - __(Alexei Mikhailov)__ Redis options are now passed directly to Redis constructor
 * 2013-04-10 [12f5fc0](../../commit/12f5fc0) - __(Alexei Mikhailov)__ Fixed #12: removed dependency from bundler in resque-status
 * 2013-04-09 [f0f825c](../../commit/f0f825c) - __(Alexei Mikhailov)__ Version bump to 0.1.5
 * 2013-04-09 [7726900](../../commit/7726900) - __(Alexei Mikhailov)__ resque-multi-job-forks recovered + refactoring
 * 2013-04-08 [3ee123e](../../commit/3ee123e) - __(Alexei Mikhailov)__ Version bump to 0.1.4
 * 2013-04-08 [49a2a0b](../../commit/49a2a0b) - __(Alexei Mikhailov)__ Revert reconnect hook for redis-3.x
 * 2013-04-08 [dbd671b](../../commit/dbd671b) - __(Alexei Mikhailov)__ Version bump to 0.1.3
 * 2013-04-08 [10201e4](../../commit/10201e4) - __(Alexei Mikhailov)__ Reestablish redis connection in each new fork
 * 2013-04-05 [5274eeb](../../commit/5274eeb) - __(Alexei Mikhailov)__ Version bump to 0.1.2
 * 2013-04-05 [1cbacab](../../commit/1cbacab) - __(Alexei Mikhailov)__ Parallel workers restart
 * 2013-04-04 [913cbf8](../../commit/913cbf8) - __(Alexei Mikhailov)__ resque-failed-job-mailer integration
 * 2013-04-03 [f0498d4](../../commit/f0498d4) - __(Alexei Mikhailov)__ Continuous jobs functionality
 * 2013-04-03 [d0868bb](../../commit/d0868bb) - __(Alexei Mikhailov)__ Rails resque initializer
 * 2013-04-02 [83fcadb](../../commit/83fcadb) - __(Alexei Mikhailov)__ Version bump to 0.1.0
 * 2013-04-02 [ec7b4e5](../../commit/ec7b4e5) - __(Alexei Mikhailov)__ Конфигурирование переменных окружения
 * 2013-04-02 [7e065be](../../commit/7e065be) - __(Merkushin)__ fix typo in file name
 * 2013-04-02 [dcca754](../../commit/dcca754) - __(Merkushin)__ fix typo in file name
 * 2013-04-01 [5a7c801](../../commit/5a7c801) - __(Alexei Mikhailov)__ Uniquiness functions extracted to separate module
 * 2013-03-28 [f9c47e6](../../commit/f9c47e6) - __(Alexei Mikhailov)__ Initial commit
 * 2013-03-28 [a2410e6](../../commit/a2410e6) - __(Alexei Mikhailov)__ Initial commit