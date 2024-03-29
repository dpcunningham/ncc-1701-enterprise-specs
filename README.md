# ncc-1701-enterprise-specs
NCC-1701: Specifications (via Repository Issues and Epics) for the Construction of the [USS Enterprise](https://www.startrek.com/database_article/enterprise).

Populates associated GitHub [project board](https://help.github.com/en/articles/about-project-boards):  [`ncc-1701-enterprise-timeline`](https://github.com/dpcunningham/ncc-1701-enterprise-specs/projects).

...which is upstream from:
- [`ncc-1701-enterprise-code`](https://github.com/dpcunningham/ncc-1701-enterprise-code): an associated GitHub "code" repository which holds issues and epics transferred from *this* "spec" repository -- according to the timeline project board on the line above;
- [`ncc-1701-enterprise-build`](https://github.com/dpcunningham/ncc-1701-enterprise-code/projects): a "swim lane" GitHub project board depicting task assignments across available crew, using cards (containing issues & epics) transfered into the code repository.



---

### Purpose

This fictional project is a benchmark for a _"leanest possible"_ workflow process tied as closely as possible to a developer's day-to-day toolset and workflow within the GitHub ecosystem, according to the following premises:

- Top-notch development talent is a very constrained resource.  
- Typical "top down" project management tools inflict a heavy toll on developer focus & energy due to forced mental context switching.  
- Organizations can avoid this unnecessary friction by adopting management practices which seek to leverage the existing toolsets already in use by experienced developers.  
- Flipping the typical project management process on its head provides welcome relief to busy developement teams, and can yield additional unanticipated benefits. 
- Finally, an understanding of the bigger "business landscape" around the GitHub ecosystem shows why using tools external to Github is (in the longer term) a non-viable approach

Details of this argument are provided in the associated [project wiki](https://github.com/dpcunningham/ncc-1701-enterprise-specs/wiki/A-Lean-Project-Management-Workflow-Based-Entirely-Within-GitHub) (bulletin board), which demonstrates another valuable tool (i.e. organized knowledge collection) for project management in this lean workflow based entirely within GitHub.


---

### Organization -- Five Basic Components:

1. _This_ **spec repository**: collects the various features (as issues and epics);
2. An associated [**timeline project board**](https://github.com/dpcunningham/ncc-1701-enterprise-specs/projects): batches the features into staged releases;
3. A partnered "downstream" [**code repository**](https://github.com/dpcunningham/ncc-1701-enterprise-code): periodically accepts batches of features (as issues & epics) based on the timeline project board. Also contains bug issues discovered during testing and in production;
4. ...with its own associated [**build project board**](https://github.com/dpcunningham/ncc-1701-enterprise-code/projects): assigns specific issues to available crew. 
5. Each repository has an associated wiki (bulletin board) which can be used to organize a [**project knowledge base**](https://github.com/dpcunningham/ncc-1701-enterprise-specs/wiki).


...created in this order (GitHub-specific workflow):
  1. Create the spec repository
  2. Within the spec repository, create:
     1. The timeline project
     2. Tie it back to the spec repository
  3. Create the code repository
  4. Within the code repository, create:
     1. The build project
     2. Tie it back to the code repository

--- 

### Resources

- The "md" suffix on this `README.md` file indicates it's a ["markdown"](https://en.wikipedia.org/wiki/Markdown) file. Here is a useful "beginner's guide" to the [specific markdown dialect](https://help.github.com/en/articles/basic-writing-and-formatting-syntax) (i.e. the "flavor" of markdown) used on GitHb.
- Here is a collection of useful GitHub guides for the various processes in this lean workflow:
  - [About Project Boards...](https://help.github.com/en/articles/about-project-boards)
  - [Creating a Project Board...](https://help.github.com/en/articles/creating-a-project-board)
  - [Adding notes to a project board...](https://help.github.com/en/articles/adding-notes-to-a-project-board#converting-a-note-to-an-issue)
  - [Converting a note to an issue...](https://help.github.com/en/articles/adding-notes-to-a-project-board#converting-a-note-to-an-issue)
  - [Transferring an issue to another repository...](https://help.github.com/en/articles/transferring-an-issue-to-another-repository)

