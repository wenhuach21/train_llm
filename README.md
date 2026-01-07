toy experiments, just for learning

CUDA_VISIBLE_DEVICES=1,2,3,4 torchrun --nproc_per_node=4 train_qwen3.py --with_tracking
