
For newcomers in the field of deep learning, it is very hard to find a suitable combination of network architecture and hyper-parameters. Mcfly is a tool that tries to do this automatically by generating and evaluating many combinations. For mcfly there are two things holding dissemination back: experiments and visualization.

To show the world that mcfly is an effective tool, experiments need to be done to compare the performance of mcfly's models to other methods on suitable datasets. Finding suitable datasets might not be easy, as we need datasets with the following properties: 
* The dataset should consist of time series and must be labeled. 
* There should be enough data to train and test on. 
* Individual data segments should ideally be independent from one another.
* Results from other classification methods should have been reported for the dataset already to have something to compare mcfly to. 
If we would have one or more of such datasets, publishing anything about mcfly would be much easier.

New and better visualizations are needed for three reasons. Better visualizations will help analysis of the deep learning process. Also, because mcfly is a tool aimed at deep-learning-novices, visualizations are needed to convey the concepts of the deep learning to the user. Finally, better visualizations allows us to make more interesting and attractive visual material to put into screen-casts/presentations/posters/blog-posts. In mcfly's issue tracker there are already a couple of ideas for work on visualizations. These include tidying up the current visualizations, adding a visualization of the used network architecture (for example blocks), and adding a visualization that shows node activations for the input data.

Other things that could be done is adding end2end testing, setting up an online demo (very small task in this case), and adding dependency tracking. Work on any of the above tasks will help a lot. Which of these tasks we'll work on, depends largely on the composition of the team.
