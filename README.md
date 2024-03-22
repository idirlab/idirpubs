# Archives of IDIR's Publications, Submissions, Reviews, and Presentations

## __1.__ __File Organization__
   * There are separate folders for submissions, reviews, publications, presentations. 
   * Submissions and reviews are organized into folders, one for each project.
   * Publications (e.g., camera-ready of accepted papers) and presentations (posters, talks) are organized by years. 

## __2.__ __Required Materials__
   * All files should follow the naming conventions outlined in [**Item 6**](#6-naming-conventions) below.
   * For each submission, archive **four** things:
     * In the project's folder under "submissions":  
       * PDF
       * The compressed tarball (.tar.gz)
     * In the project's folder under "reviews": 
       * The reviews
       * The review summary (if applicable) 
   * For each publication, archive **three** things:
     * PDF
     * The compressed tarball
     * A thumbnail image (if applicable)
   * For each presentation, archive **two** things:
     * PDF
     * PPT (or other original file used for generating the PDF)

## __3.__ __What to Include in the Tarball__
   * LaTeX source files
   * Images (i.e., eps, png, jpg, etc. files used for figures in the paper)
   * Raw Excel, PowerPoint, etc. files
   * Raw experiment result files used for producing figures or tables

## __4.__ __What NOT to Submit__
   * Project source code
   * Data
   * Experiment-related files not used for producing figures or tables
   * **_`Anything falling under the umbrella of the above should be archived in the individual project's GitHub repository,` not in this repository._**

## __5.__ __Other Guidelines__
   * When naming files, `[`_papername_`]` can be the project's codename or an intuitive name for the paper topic.
   * Use lowercase abbreviation for months (e.g., "jan" instead of "January").

## __6.__ __Naming Conventions__
   ### _a. Conference/Workshop Submission_
   * `[`_papername_`]-[`_venue_`][`_year_`]-[`_first author last name_`]-submission`
       * pareto-icde15-asudeh-submission
       * gqbe-grades14-jayaram-submission
   ### _b. Demo/Poster Submission_
   * `[`_papername_`]-[`_venue_`][`_year_`]`_demo/poster_`-[`_first author last name_`]-submission`
       * factwatcher-vldb14demo-hassan-submission
       * wikiclassification-cikm12poster-sultana-submission
   ### _c. Journal Submission_
   * `[`_papername_`]-[`_venue_`]-[`_first author last name_`]-submission-[`_month of submission_`][`_year of submission_`]`
       * gqbe-tkde-jayaram-submission-may14
   ### _d. Journal Revision_
   * `[`_papername_`]-[`_venue_`]-[`_first author last name_`]-[`_revision number such as R1, R2..._`]-[`_month of revision submission_`][`_year of revision submission_`]`
       * skylinegroup-tkde-hassan-R1-apr13
   ### _e. Conference/Workshop & Demo/Poster — Camera-Ready Version_
   * Remove `-submission` from the first two rules, [**a.**](#a-conferenceworkshop-submission) and [**b**](#b-demoposter-submission).,  for conference/workshop and demo/poster submissions, respectively.
       * factmonitoring-icde14-sultana
   ### _f. Journal Final Version_
   * `[`_papername_`]-[`_venue_`]-[`_first author last name_`]-[`_month of final version submission_`][`_year of final version submission_`]`
       * streak-tkdd-zhang-sept13
   ### _g. Presentations_
   * Follow the same naming rules in [**e.**](#e-conferenceworkshop--demoposter--camera-ready-version), followed by either `-talk` for multi-slide presentations or `-poster` for large single-slide presentations. 
       * claimbuster-cikm15-hassan-poster
       * claimbuster-cj15-hassan-talk
   * Note that the term `poster` can mean two different things in the naming convention—as in "poster track" of a conference or as in "the slide of a poster presentation". So we may have a file such as xyz-abc15poster-joe-poster, which means the poster (i.e., single large slide) for a poster paper. 
