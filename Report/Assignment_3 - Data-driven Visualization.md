# Assignment 3 : Data-driven Visualization

In this assignment we will use the taxonomy described in two academic papers to describe two data-driven visualizations created in the year 2019. The academic papers are:

1. [Narrative Visualization](http://doi.org/10.1109/TVCG.2010.179) by Segel and Heer
1. [Watch this: A taxonomy for dynamic data visualization](http://doi.org/10.1109/VAST.2012.6400552) by Cottam et al

And the link for the two data-driven visualizations are:

1. [Behold the most complete map of American breweries ever](https://www.fastcompany.com/90303261/behold-the-most-complete-map-of-american-breweries-ever)<a name="one"></a>
1. [Goodbye, Mid-Range Shot](https://flowingdata.com/2019/01/15/goodbye-mid-range-shot/)<a name="two"></a>

We will start with the visualization of American Breweries.

## 1. American Breweries Map

The image below shows the visualization.

![American Breweries Map](https://images.fastcompany.net/image/upload/w_937,ar_16:9,c_fill,g_auto,f_auto,q_auto,fl_lossy/wp-cms/uploads/2019/02/p-1-90303261-behold-the-most-complete-map-of-american-breweries-ever.jpg "American Breweries Map")

I will be using the insights from paper [[1]](#one) as this visualization does not include dynamic data. The paper defines the design space of narrative visualization as having three dimensions: *(1) genre, (2) visual narrative tactics, and (3) narrative structure tactics*. The dimesions are further divided into the following major sections.

1. Genre 

    * Magazine Style
    * Annotated Graph / Map
    * Partitioned Poster
    * Flow Chart
    * Comic Strip
    * Slide Show
    * Film / Video / Animation


2. Visual Narrative

    * Visual Structuring
    * Highlighting
    * Transition Guidance
 

3. Narrative Structure

    * Ordering
    * Interactivity
    * Messaging
    
The sections of the visual and narrative dimesions are further divided into multiple design elements which we will delve into as we analyse the visualization.

We first start with finding the *Genre* of the visualization from the list provided in the paper. Based on the descriptions of the different genres provided in the paper, I classify the American breweries visualization as belonging in the **annotated graph / map** genre as the visualization shows all the breweries on the United States map.

Now we move onto the second dimesion i.e *visual narrative tactics* used in the visualization. 

The *Visual Structuring* section of this dimension has four design elements: *(1) establishing shot, (2) consistent visual platform, (3) progress bar, and (4) checklist progress tracker*. I only find the **consistent visual platform** design element to be present in this visualization.

The *Highlighting* section has six further design elements: *(1) close-ups, (2)
feature distinction, (3) character direction, (4) motion, (5) audio, and (6) zooming*. From these, I find the visualization to contain **close-ups, feature distinction and zooming** elements. The regions in the map are color coded to shows the density of the breweries in each state. Also areas where density is more are focused into separate circles to show details. 

The *Transition Guidance* section has six design elements: *(1) familiar objects, (2) Viewing angle, (3) viewer motion, (4) continuity editing, (5) object continuity, and (6) animated transitions*. This visualization has **familiar objects and object continuity** present in it as rest all the elements pertain to dynamic visualizations.

We now move to the last dimension i.e *narrative structure tactics* for our analysis.

The Ordering section has three elements *(1) random access, (2) user directed path, and (3) linear*. Even though there is no suggested path in the map (random access), in order to get more details of a dense region the user has to follow the suggested path (linear) in the visualization. But ultimately the map has no prescribed direction so it has **random access** design element.

The Interactivity section pertains to dynamic data and it is not found in this visualization.

We now focus our attention to the last section *Messaging* for this visualization. This section has seven elements *(1) captions, (2) annotations, (3) accompanying article, (4) multi-messaging, (5) comment repitition, (6) introductory text, and (7) summary*. We can observe that the visualization has **captions and annotations** elements. As observed in the paper that narrative visualizations usually do not contain elements from this section.

Also, from the three common design schemas described in the paper viz. *(1) martini glass structure, (2) interactive slideshow, and (3) drill-down story* this visualization according to me follows the **drill-down story** pattern more closely sans the interactive feature included in it.

The visualization is pretty straightforward with not much analysis is done of the data. The difficulty arises in getting an accurate data for all the brewries in the United States. This does not increase the complexity of the visualization though.

Including all, the visualization is effective in communicating its explicit stated purpose of showing every brewery in United States. 

## 2. Midrange Shot Selection

The image below shows the visualization of the NBA shot selection over the years.

![Midrange shot selection](https://i1.wp.com/flowingdata.com/wp-content/uploads/2019/01/shot-selection2010-19-1.gif?resize=750%2C618&ssl=1 "Midrange shot selection")

As this visualization includes dynamic data we will employ the insights from both [[1]](#one) and [[2]](#two) papers to analyze this visualization.

The second paper defines two dimensions of the visual space: *(1) spatial variables and (2) retinal variables* and each is further divide into four categories. The rest of the paper is concerned with the streaming data which is not applicable in this visualization. Nevertheless, we will use the taxonomy to analyze the visualization and then use the insights from the first paper to further discuss about the visualization.

The four categories for each variables are defined as follows:

1. Spacial variables
    
    * Fixed
    * Mutable
    * Create
    * Create & Delete


2. Retinal variables

    * Immutable
    * Known Scale
    * Extreme Bin
    * Mutable Scale
 
 
Based on the desciption provided in the paper for each of the 16 combinations of these variables, I find this visualization to the **FIXED x EXTREME BINS** category as the spacial variables in the data are not changing and any new data in the visualization takes the value within the specified range.

Now we will use the design space dimensions from the first paper to further analyze the visualization.

The *Genre* of the visualization here is again **annotated graph / map** in this case but also with some **film / video / animation** elements.

Next, we move to the *visual narrative tactics* of the visualization.

From the *Visual Structuring* section, this visualization has two elements specified: **establishing shot and consistent visual platform**. This visualization does contain an initial shot of the season 2009-10 and then compares the next seasons with this season. As there is a consistent visual style for showing the magnitude.

The elements from the *Highlighting* section observed are **feature distinction and motion**. This visualization does not include any *close-ups or zooming* like the previous visualization but does include a dynamic element of *motion* in it. Like the previous case, the visualization does uniquely identify separate features.

This visualization does include some interesting elements from the *Transition Guidance* section. The elements observed are **familiar objects, object contibuity and animated transitions**. All these elements are self evident in the visualization.

Lastly, we look into the *narrative structure tactics* dimension of the design space.

The *Ordering* here is **linear** as the entire visualization is author-driven. The user has no control over any of the elements of the visualization.

The *Interactivity* section which was left unexplored in the last visualization still remains out of reach in this visualization as it provides no interactivity. Nonetheless, I will list the design elements it contains: *(1) hovering / details, (2) filtering, (3) navigation buttons, (4) very-limited interactivity, (5) explicit instruction, (6) tacit tutorial, and (7) stimulating default views*.

Finally, we come to the *Messaging* section of the design space. We can observe that it includes **captions, annotations and summary** elements. *captions and annotations* are simple to observe but the **RIP Mid-Range** text at the end of the visualization does constitute as a summary of the visualization. This does give it an interesting way to end the visualization.

Like the previous visualization, this visualization according to me successfully supports the narrative it tries to convey. Unlike the previous visualization, the article of the visualization included further graphs to support this visualization. How those extra visuals aid in interpreting this visualization is something I find to be worth of analysis. This visualization is more complex that the previous one as it tries to compare data across time which requires complex analysis. So it increases the difficulty in constructing this visualization as compared to the previous one.

Lastly, I would like to provide an analysis of a visualization having interactive elements which remained out of our purview in this assignment as interactive elements entail *rich and complex* data visualizations.