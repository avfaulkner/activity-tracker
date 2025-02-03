# activity-tracker

Task management tracker where users can create tasks which are tracked and displayed in a real-time activity feed.

## Components

- Authentication & Authorization (Devise or custom)
- Activity Feed using ScyllaDB
- Full-Text Search using ElasticSearch
- Caching & Queue Management with Redis
- Data Storage using MySQL & PostgreSQL
- Continuous Deployment with CircleCI & GitHub Actions
- Containerization & Orchestration with Docker and Kubernetes

## Steps

Install Rails

```
sudo apt  install ruby-rubygems
gem install rails
```

Create a new Rails app with PostgreSQL as the default database

```
rails new activity_tracker --database=postgresql
```

Navigate to the project directory

```
cd activity_tracker
```
