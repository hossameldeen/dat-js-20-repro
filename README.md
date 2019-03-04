# dat-js #20 repro

A reproduction for [dat-js/#20](//github.com/datproject/dat-js/issues/20).

## Steps
- `yarn install`

- `yarn run start`

- Open `localhost:5000/first-run.html` in the browser & open the console.

- You'll find that write happens successfully. Wait till you see `closed` log.

- Open `localhost:5000/second-run.html` in the browser & open the console.

- You'll see that `repo.ready` callback is indeed called but `readFile` callback is not :(.

