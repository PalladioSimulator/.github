## Palladio Simulator

Palladio is a well-validated approach for the prediction of Quality of Service (QoS) properties of component-based software architectures. It enables the creation of high quality software architectures with dependable quality properties.

[Numerous publications](https://dsis.kastel.kit.edu/research/publications.php) demonstrate the applicability of Palladio for scientific and real-world industrial scenarios of different domains. Ongoing development effort and the continuous integration of latest scientific trends provides cutting-edge features to researchers and practictioners.

From a scientific perspective, Palladio comprises
- The [Palladio Component Model (PCM)](https://github.com/PalladioSimulator/.github/wiki/Palladio-Component-Model), a detailed meta-model of component-based software architectures.
- A component-based software development process. Palladio is aligned with this process and enables distributed modeling for component-based software development scenarios.
- A software architecture simulator: Multiple performance, reliability, maintainability, and cost prediction [approaches](
https://github.com/PalladioSimulator/.github/wiki/Quality-Dimensions) are combined. The approaches, by means of analysis or simulation, calculate metrics (e.g. response time) from Palladio models (instance of the PCM).
- Tool support: the [Palladio-Bench](https://github.com/PalladioSimulator/.github/wiki/Palladio-Tools) implements all aspects of Palladio. It is extendable in such a way that it can serve as an implementation base for new scientific directions.

More information on the scientific background of Palladio and developer information can be found in the [GitHub Wiki](https://github.com/PalladioSimulator/.github/wiki).

The development of the Palladio [started back in 2003]([https://www.palladio-simulator.com/about/history/](https://github.com/PalladioSimulator/.github/wiki/History)) at the University of Oldenburg, and is nowadays developed at [Karlsruhe Institute of Technology (KIT)](http://www.kit.edu/english/), [FZI Research Center for Information Technology](http://www.fzi.de/en), and [Paderborn University](http://www.uni-paderborn.de/en/). Further scientific cooperations and research partners contribute in terms of scientific exchange and tool development.

Current research topics include for example

- Model-driven development (MDD/MDSD)
- Cloud computing and virtualisation
- Outsourcing / offshoring
- Performance cockpit for large-scale application measurement and forecasting
- Automated design optimisation
- Reverse engineering

### Integrate and cooperate with Palladio

The [Palladio-Bench](https://github.com/PalladioSimulator/.github/wiki/Palladio-Tools) is open source tool support for the Palladio approach. Also Palladio research is open to external contributors, research cooperations, researcher which like to extend Palladio, and users who like to use Palladio “as-is”.

Options to integrate in Palladio include

- Use Palladio as software architecture simulator
- Contribute new analysis or simulation approaches for the existing Palladio Component Model (PCM)
- Add new quality dimensions to Palladio (either PCM or analysis)
- Extend the PCM’s meta-model by new entities and concepts
- Integrate Palladio in your development processes
- Apply Palladio to new problem domains
- Develop new editors and views for software architecture models
- Use the PCM a research object (e.g. long-term history of the PCM)
- Develop complementary tooling for the Palladio-Bench

[Contact us](https://www.palladio-simulator.com/contact) to get in touch and propose your own topics.

### Scientific Literature and Documentation

Here you will find a selection of core scientific literature and documentation of Palladio. General information is available here, tool-related documentation (tutorials and screencasts) is located in the tools section, and developer-related documentation is placed in the Palladio Developer Wiki.

#### Palladio Book
The creators of Palladio have published a dedicated book *Modeling and Simulating Software Architectures – The Palladio Approach*, which desciribes key concepts of Palladio’s domain-specific modeling language for software architecture quality and presents the corresponding development stage.
You can find more information on the following sites:
* [Google Books](https://books.google.de/books?id=QztMDQAAQBAJ&printsec=frontcover)
* [MIT Press](https://mitpress.mit.edu/9780262034760/modeling-and-simulating-software-architectures/)
* [KIT Library](https://publikationen.bibliothek.kit.edu/1000071486)

#### Key Publications in English

- [Overview of the Palladio Component Model](https://www.palladio-simulator.com/assets/files/Introduction-Chapter-PCM.pdf) (28 pages, PDF): Palladio introductive paper
- WOSP paper, “Model-Based Performance Prediction with the Palladio Component Model”: The Palladio approach in short (11 pages, PDF, won ACM Best Paper Award at WOSP2007)
> Steffen Becker, Heiko Koziolek, and Ralf H. Reussner. Model-based Performance Prediction with the Palladio Component Model. In WOSP ‘07: Proceedings of the 6th International Workshop on Software and performance, pages 54-65, New York, NY, USA, February 5-8 2007. ACM.

- Technical Report: “The Palladio Component Model”: Deals only with the (meta-)model, not the analysis techniques, simulation, and code generation. Contains the generated documentation of the PCM metamodel. (193 pages, PDF)
> Ralf Reussner, Steffen Becker, Erik Burger, Jens Happe, Michael Hauck, Anne Koziolek, Heiko Koziolek, Klaus Krogmann, and Michael Kuperberg. The Palladio Component Model. Karlsruhe Reports in Informatics 2011,14, Karlsruhe, 2011.

- [IEEE TSE paper](http://dx.doi.org/10.1109/TSE.2011.94): “Architecture-Based Reliability Prediction with the Palladio Component Model”: Focus on reliability prediction with Palladio (29 pages, PDF, requires IEEE access)
> Franz Brosch, Heiko Koziolek, Barbora Buhnova, and Ralf Reussner. Architecture-based reliability prediction with the palladio component model. Transactions on Software Engineering, 38(6), 2011.

- [IEEE Software paper](http://dx.doi.org/10.1109/MS.2011.25), “Facilitating Performance Predictions Using Software Components”: Easy to understand overview on the Palladio approach (7 pages, requires IEEE access)
> Jens Happe, Heiko Koziolek, and Ralf Reussner. Facilitating performance predictions using software components. Software, IEEE, 28(3):27 -33, may-june 2011.

- [Journal of Systems and Software (JSS) paper](http://dx.doi.org/10.1016/j.jss.2008.03.066), “The Palladio component model for model-driven performance prediction”: The MediaStore example system (19 pages, requires Science Direct/Elsevier access)
> Steffen Becker, Heiko Koziolek, and Ralf Reussner. The Palladio component model for model-driven performance prediction. Journal of Systems and Software, 82:3-22, 2009.

A full list of publications, mostly related to Palladio, is available in our [full publication list](https://sdq.ipd.kit.edu/research/publications/). The “[Karlsruhe Series on Software Design and Quality](https://sdq.ipd.kit.edu/research/karlsruhe-series-on-software-design-and-quality/)” has full details on the scientific background of Palladio.
