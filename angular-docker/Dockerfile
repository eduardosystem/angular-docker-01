from public.ecr.aws/docker/library/alpine:edge

WORKDIR /app

COPY . ./

RUN npm install

RUN npm run build