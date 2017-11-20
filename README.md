# 4차산업혁명 선도인재 양성 프로젝트 과정

---
## 1. Week 1 Day 9:

## Cron linux



##### gem whenever

+ https://github.com/javan/whenever

생성한 폴더에서 wheneverize.

mkdir config

Rakefile 생성저장

```ruby
namespace :telegram do
  task :hello do
    puts "hello!!!"
  end
end
```

rake "telegram:hello"

rake : task batch파일



```ruby
namespace :db do
  task :migrate do
    puts "rake db:migrate가 실행되었습니다."
  end
end
```

https://bluesh55.github.io/2016/10/23/rake-task/



##### AWS secret key 환경변수 시

gem figaro

echo $IP == puts ENV[IP]

ruby environment variable
