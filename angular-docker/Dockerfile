from public.ecr.aws/docker/library/alpine:edge

RUN apk --no-cache add nodejs npm

WORKDIR /app

COPY . ./

RUN npm install

RUN npm run build
#RUN ng serve