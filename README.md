# codecentric DL deep dive
Dockerfile for the codecentric deep learning deep dive

## Build locally

```bash
git clone https://github.com/bbesser/codecentric.dldeepdive.git
cd codecentric.dldeepdive

docker build -t codecentric.dldeepdive .

docker run -p 8888:8888 -v $(pwd)/notebooks:/notebooks -v $(pwd)/data:/data codecentric.dldeepdive
```
