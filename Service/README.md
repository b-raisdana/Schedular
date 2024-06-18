* /api/Scheduler/task(same as /RabbitMQ/Scheduler/scheduled_task_request_consumer)
* /RabbitMQ/Scheduler/scheduled_task_request_consumer(uri: str, parameters: str(JSON({name: str -> value: Any})),
  method:[‘GET’ | ‘POST’], schedule:  (Crontab | [Crontab]), requester_id: uuid, requester_signature: str(MD5))