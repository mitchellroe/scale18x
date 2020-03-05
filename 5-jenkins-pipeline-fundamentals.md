# Workshop: Jenkins Pipeline Fundamentals

- Don't over-engineer your pipeline scripts. Do most of your logic in your own
  build system. Pipeline as glue, not bricks.
- Declarative should account for most of your use cases. Scripted pipelines are
  more customizable, but not as easy to work with.
- http://student-55.training-pipeline-fundamentals.class-scale18x.cloudbees-training.com:5000/
- Artifacts
    - Artifacts _should_ be kept in their own, dedicated artifacts repository,
      but Jenkins can keep track of them.
    - Jenkins makes checksums of artifacts and keeps track of them that way.
- `failfast true` if you want it to stop all parallel jobs immediately upon any
  one parallel test failing
- Scripted pipeline
    - Older, "lower level" language
    - Know that it exists, but avoid using it if you can
- Agent scope
    - Set to 'none' at the start and you can ask questions of the user without
      allocating an agent to do so.
- https://go.cloudbees.com/training
