# dsh-superagent-playground

Sandbox for dsh-superagent: issues here are handled by the agent account `@yy1844`.

- Panel: `http://127.0.0.1:3082/` (DSH profile `superagent`, separate from the daily profile)
- Trigger: an issue or comment that mentions `@yy1844`, written by an account on the Policy allowed list
- Issues and comments written by the agent account itself never trigger (the source skips its own account), so a second account must start the work

To file work, use the **交给 agent 的工单** issue template and fill its five parts: goal, location, acceptance criteria, out of scope, context.
本行由 superagent 冒烟测试添加。
