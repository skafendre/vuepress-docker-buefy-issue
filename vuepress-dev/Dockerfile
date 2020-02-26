FROM node:latest

RUN git clone https://github.com/skafendre/vuepress-docker-buefy-issue.git

# dev
RUN npm --prefix ./vuepress-docker-buefy-issue i
CMD ["npm", "run", "--prefix", "./vuepress-docker-buefy-issue", "dev"]

EXPOSE 8080

# docker image build cmd :
# docker build -t debug/vuepress-docker-buefy-issue ./vuepress-dev
#
# docker image run cmd :
# docker run -p 8080:8080 debug/vuepress-docker-buefy-issue
