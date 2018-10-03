
* git clone git@github.com:demon1996/larabbs.git
* cp .env.example .env
* 修改.env配置
* composer install
* php artisan key:generate
* php artisan migrate:refresh --seed
* yarn install
* npm run watch
* 设置计划任务 export EDITOR=vi && crontab -e
  添加 * * * * * php /....../larabbs/artisan schedule:run >> /dev/null 2>&1