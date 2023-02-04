FROM pytorch/pytorch:1.13.1-cuda11.6-cudnn8-runtime

RUN pip install ipykernel && \
        python -m ipykernel install --sys-prefix    

RUN pip install -q --upgrade pip \
        merlin-core \
        merlin-models \
        merlin-systems \
        nvtabular \
        transformers4rec[pytorch,nvtabular,dataloader]
