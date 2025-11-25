# mjlab_go2

```sh
MUJOCO_GL=egl uv run mjlab_train Mjlab-Velocity-Rough-Unitree-Go2 --env.scene.num-envs 4096 --agent.max-iterations 10000 --video True --video-length 100 --agent.logger tensorboard
```

```sh
uv run mjlab_play Mjlab-Velocity-Rough-Unitree-Go2 --checkpoint-file [path-to-checkpoint]
```
