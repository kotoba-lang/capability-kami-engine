# capability-kami-engine

Atomic authority package for `kami/engine`.

- imports: `#{:kami-despawn-within! :kami-axis :kami-set-velocity! :kami-nearest-tagged :kami-despawn :kami-tick-n :kami-get-z :kami-get-x :kami-get-y :kami-count-tagged :kami-set-position3! :kami-move-tagged-toward! :kami-set-velocity3! :kami-spawn :kami-rand :kami-set-position!}`
- effects: `#{:simulation-read :randomness :simulation-write}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
