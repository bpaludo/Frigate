# palalab

Arquivos de configuração do Frigate. 
Camera Moes Tuya. Codec H264 (nao pode ser alterado) e PCMA (nao pode ser alterado)
GMKTEC G3 Com N100
Vaapi e Open Vino ativados

Criar LXC Debian com as configs:
Privilegiado, Nesting, Mount Options Discard, Usar todos os cores menos 1, 4gb de ram, network desabilitar firewall e colocar dhcp em ipv4 e ipv6. Depois de criar habilitar Fuse em Options


https://github.com/blakeblackshear/frigate/discussions/5773

https://github.com/jsapede/frigate-proxmox-docker-openvino?tab=readme-ov-file

https://docs.frigate.video/configuration/object_detectors/#openvino-detector

https://colab.research.google.com/github/blakeblackshear/frigate/blob/dev/notebooks/YOLO_NAS_Pretrained_Export.ipynb#scrollTo=uBhXV5g4Nh42


