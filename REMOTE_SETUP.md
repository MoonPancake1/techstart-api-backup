# Remote Repository Setup

## Current Remotes
backup	git@github.com:MoonPancake1/techstart-api-backup.git (fetch)
backup	git@github.com:MoonPancake1/techstart-api-backup.git (push)
origin	git@github.com:MoonPancake1/techstart-api.git (fetch)
origin	git@github.com:MoonPancake1/techstart-api-backup.git (push)

## Tracking Branches
  develop fd7935a New version
* main    8057525 New func for api

## Fork Workflow Summary
- Original repository: https://github.com/MoonPancake1/techstart-api
- Fork repository: https://github.com/vlad08chern-arch/awesome-calculator
- Upstream configuration: git remote add upstream https://github.com/MoonPancake1/techstart-api

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command: git config --add remote.origin.pushurl https://github.com/MoonPancake1/techstart-api-backup

## Lessons Learned
Работать с различными репозиториями тяжело и интересно! Можно разработать множество механизмов для автоматизаций и отлично управлять ими благодаря git
