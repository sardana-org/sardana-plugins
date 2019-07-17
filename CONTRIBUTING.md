# How to register a plugin project in the catalogue?

The registration process is executed via GitHub [Pull Request](https://help.github.com/articles/creating-a-pull-request/).

These are the typical steps of such a process:

1. Select the approprieate category for your plugin project.
2. Look if in the selected category exists an entry for such plugin(s) e.g. Tango entry in the Software category.
  * If there is already an entry, add your plugin project as next bullet point in that entry
  * If there is no entry, create a new one respecting the alphabetical order within the category. An entry should contain a brief
     description, for example, for what are the below listed projects?
3. Fill the following information:
  * To create a new entry use the second level markdown header: `##` with the entry name e.g. `## IcePAP`.
    Below the entry place a short description e.g. "IcePAP motion controller".
  * To add a new project within an entry use one bullet point per project `*` with the project name in bold<br/>
    e.g. `* **sardana-icepap**` and within a nested bullet points add:
    * link(s) - links to projects/artifacts
    * OPTIONAL: any othe other relevant information
4. Create a PR with the changes explained in the point 3.
