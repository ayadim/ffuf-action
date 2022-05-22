This ffuf Action makes it easy to orchestrate directory fuzzing with GitHub Action. Integrate ffuf into powerful continuous security workflows and make it part of your secure software development life cycle.

Available Inputs
------

| Key               | Description                                         | Required |
| ----------------- | --------------------------------------------------- | -------- |
| `ffuf-url`        | URL created for ffuf.                               | true     |
| `wordlist`        | Path to the wordlist file.                          | true     |
| `depth`           | Maximum recursion depth.                            | false    |
| `Threads`         | Number of concurrent threads.                       | false    |