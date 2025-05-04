


- CLIP
- ViLT


视觉问答 图文检索


Language Guided Detection
Language Guided Segmentation

文本图像生成 文本视频生成


DALLE2 / Stable Diffusion / Phenaki Video / Imagen Video



传统的多模态学习
下游任务是图文检索 
Image Text Retrieval / VQA(Video Question Answer) / Visual Reasoning / Visual Entailment


只用Transformer Encoder的一些方法 ViLT / CLIP

ALBEF VLMo


后面会讲 Transformer Encoder 和 Transformer Decoder 一起的一些方法 (BLIP / CoCa / BEIT v3 / PaLI)


## ALBEF

### Review ViLT

OSCAR / ViLBERT / UNITER 

### Review CLIP

图文匹配的任务非常在行

VQA / VR / VE 性能就不够好



###
LOSS:

ITC(Image Text Contrastive) (√)
WPA(Word Patch Alignment) 训练慢 (x)
MLM(Mask Language Modeling) (√)
ITM(Image Text Matching) (√)



## ALBEF (Align before Fuse)

后续BLIP / MUST / ALPro

LIM / momentum distillation

预训练参数用的 DEiT

Note: 读文献 做总结 才有idea