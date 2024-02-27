gpu: python test.py --rgb_path ./demo/ARAD_1K_0912.jpg  --method mst_plus_plus --pretrained_model_path ./model_zoo/mst_plus_plus.pth --outf ./exp/mst_plus_plus/  --gpu_id 0
cpu: python cpu.py --rgb_path ./demo/ARAD_1K_0912.jpg --method mst_plus_plus --pretrained_model_path ./model_zoo/mst_plus_plus.pth --outf ./exp/mst_plus_plus/
