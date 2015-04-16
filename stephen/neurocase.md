# Case study in Neurosience

## Background: sources of data

Aim for project was to collect similar data from different labs
worldwide so that we could do some meta analysis.


Data in this case: multielectrode array recordings of spontaneous
activity in developing retina.


## Approach

- Collect data and convert into a common format (HDF5).

- Curate the data ("meta data") and store electronically.

- Apply some simple analysis

- We used the knitr system in R to do our analysis.

## Results

Most tables and graphs in our report were automated and recomputed
dynamically, e.g. every time the database extended.

(Show a couple of example figures or tables along with knitr file)

## Submitting the paper

Provided all code and data online on our web page together with PDF.

Cook for one month...

## Reviews

(Aside: reviews were signed and are now public).
http://www.gigasciencejournal.com/content/3/1/3/prepub

One of the reviewers was already an expert in knitr, and queried with
the use of a log scale for one of my figures.  But as he argued it was
easy for him to regenerate the figure and include it in his review!

(Perhaps include this section of the review.)

## Post acceptance

Journal were very keen to see the reproducible research angle, so they
wrote a press-release and a couple of interviews.

Which led to a Nature Neuroscience podcast a few weeks later.

(Hint: don't be shy about contacting
http://www.communications.cam.ac.uk/)

# What next

## Journal policies are developing . . .

Since Oct 2014, Nature journals wish to see code relating to papers.

We are now working with Nature Neuroscience on how to check this.

## Badges

Kitemarking and Badges for papers/people.

## Good practice

I try to write my papers now in this format, so that I can bundle data
and code with manuscript.

Docker also makes it easy to test on fresh systems, and for others to
test:

    docker run -d -p 8787:8787 sje30/waverepo
	open http://192.168.59.103:8787/

## Live demo

Anyone with docker installed on their laptop and want to try a live
demo (apart from me?)


## Acknowledgements

* Waverepo data providers

* Ben Marwick (Docker)

* EPSRC (CARMEN), Wellcome Trust.



