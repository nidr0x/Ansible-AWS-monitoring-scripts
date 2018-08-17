Ansible-AWS-Monitoring-scripts
=========

Role for installing officially provided Perl scripts to report instance status to CloudWatch service. You will need to create a role in IAM with the next permissions:

```
    cloudwatch:PutMetricData
    cloudwatch:GetMetricStatistics
    cloudwatch:ListMetrics
    ec2:DescribeTags
```

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-aws-monitoring-scripts
```

## License

MIT
