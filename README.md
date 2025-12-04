# go2_mjlab

```sh
uv run go2_list_envs
just run go2_train Mjlab-Velocity-Rough-Unitree-Go2 --env.scene.num-envs 4096 --agent.max-iterations 10000 --video True --video-length 100 --agent.logger tensorboard
just run train Mjlab-Velocity-Flat-Unitree-G1 --env.scene.num-envs 4096 --agent.max-iterations 10000 --video True --video-length 100 --agent.logger tensorboard
```

```sh
just run go2_play Mjlab-Velocity-Rough-Unitree-Go2 --checkpoint-file [path-to-checkpoint]
just run go2_play Mjlab-Velocity-Rough-Unitree-Go2 --checkpoint-file logs/rsl_rl/go2_velocity/2025-11-30_21-43-36/model_300.pt --video True --video-length 200
```
