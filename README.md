Reduce some timeouts. In /etc/ceilometer/pipeline.yaml

    - name: cpu_source
      interval: 20
      meters:
          - "cpu"

And in /etc/ceilometer/polling.yaml

interval: 20

