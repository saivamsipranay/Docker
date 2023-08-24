FROM node:16
LABEL AUTHOR='Sai Vamsi Pranay'
RUN git clone https://github.com/Aesthisia/Assignment-L1-DO.git
RUN cd Assignment-L1-DO/aesthisia-demo && npm install
WORKDIR /Assignment-L1-DO/aesthisia-demo
EXPOSE 3000
CMD ["npm", "start"]