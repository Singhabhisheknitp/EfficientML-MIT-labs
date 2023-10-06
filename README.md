# EfficientML-MIT-labs
This Repo contains all lab work assigments & notes recorded by me during lectures as gist
Lecture 1:  The Models are outgrowing the hardware supply for AI architechture and such outpaced growth necessiates effcient hardware and efficient models 
Lecture 2: Revisiting the basics in context of focussing efficency , gist made by me after going throught the lecture 
    I. MLP layers or Feed Forwards : each output neurons are connected to input neurons \ for input (n, ci) and output (n, co)  the weight size: [c0Xci]* bit width total activations: n(c0 + ci)
    II. Convolution (1D , 2D depending upon the spatial dimension of data): mostly used to analyisce the data local patterns such as image texture , shape etc. These signals hold feature vector or channel column vector at  each spatial positions. for example in time series at every time stamp there will be channel vectors containing data info of that time stamp, or in NLP at each time sequece there will be token of some high dimensional embeddins or in Image data every (x, y) co-ordibate will have 3 channels of data RGB etc
        a. 1D convolution (time series or langauge): each output neuron is connected to input neurons in receiptive field. for input (n, ci, w)
       
  
