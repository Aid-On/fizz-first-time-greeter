# fizz-first-time-greeter

**Fizz** (AITuber system in [Almide](https://github.com/almide/almide)) — §3 brain 部品。

初見ユーザへの決定論的自己紹介を 1 回だけ。`should_greet/intro_fragments/mark_delivered` + `INTRO_DELAY_MS`。

責務は一行で、入力 → 出力が型で言い切れる単位 (openaituber `docs/almide-component-breakdown.md` §3)。

## Install

```toml
[dependencies]
fizz_first_time_greeter = { git = "https://github.com/Aid-On/fizz-first-time-greeter", tag = "v0.1.0" }
```

## Tests

```bash
almide test
```

純ロジックなのでネットワーク・API キー不要でテストできる。
