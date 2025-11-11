---
icon: fas fa-gears
order: 4
---

### [Goéland](https://github.com/GoelandProver/Goeland) 🐦

Work done in collaboration with [David Delahaye](https://www.lirmm.fr/~delahaye/), [Isaac Lluís](http://isaac-lluis.com/) and [Johann Rosain](https://perso.ens-lyon.fr/johann.rosain/). 

Goéland is an automated theorem prover for first-order logic with equality. It relies on a
concurrent proof-search procedure based on the method of free-variable analytics tableaux that
allows it to perform a fair branch exploration. The prover is also able to deal with axiomatisable
theories thanks to a module of deduction modulo theory, to deal with polymorphic types,
and to produce machine-checkable proofs in Coq, Lambdapi and Lisa.

<details>
  <summary>Please refer to <a href="{{ site.url }}{{ site.baseurl }}/assets/bibtex/ijcar2022.txt"> this paper</a> if you want to cite Goéland:</summary>

<div>
<pre>
@inproceedings{cailler2022goeland,
  author       = {Julie Cailler and
                  Johann Rosain and
                  David Delahaye and
                  Simon Robillard and
                  Hinde Lilia Bouziane},
  editor       = {Jasmin Blanchette and
                  Laura Kov{\'{a}}cs and
                  Dirk Pattinson},
  title        = {Go{\'{e}}land: {A} Concurrent Tableau-Based Theorem Prove (System Description)},
  booktitle    = {Automated Reasoning - 11th International Joint Conference, {IJCAR} 2022, Haifa, Israel, August 8-10, 2022, Proceedings},
  series       = {Lecture Notes in Computer Science},
  volume       = {13385},
  pages        = {359--368},
  publisher    = {Springer},
  year         = {2022},
  url          = {https://doi.org/10.1007/978-3-031-10769-6\_22},
  doi          = {10.1007/978-3-031-10769-6\_22}
}
</pre>
</div>

</details>



### [SC-TPTP Utilities](https://github.com/SC-TPTP/sc-tptp) 📜

Work done in collaboration with [Simon Guilloud](https://simonguilloud.ch/).

SC-TPTP Utilities is a library of tools able to deal with the SC-TPTP format. It includes softwares able to handle, import, export and transform proofs in SC-TPTP format, to add intermediate proof steps, and to export them into Rocq. 

<details>
  <summary>Please refer to <a href="{{ site.url }}{{ site.baseurl }}/assets/bibtex/cade30.txt"> this paper</a> if you want to cite SC-TPTP utilities:</summary>

<div>
<pre>
@inproceedings{10.1007/978-3-031-99984-0_18,
author = {Guilloud, Simon and Cailler, Julie and Gambhir, Sankalp and Poiroux, Auguste and Herklotz, Yann and Bourgeat, Thomas and Kun\v{c}ak, Viktor},
title = {Interoperability of&nbsp;Proof Systems with&nbsp;SC-TPTP},
year = {2025},
isbn = {978-3-031-99983-3},
publisher = {Springer-Verlag},
address = {Berlin, Heidelberg},
url = {https://doi.org/10.1007/978-3-031-99984-0_18},
doi = {10.1007/978-3-031-99984-0_18},
abstract = {We introduce SC-TPTP, an extension of the TPTP derivation format that supports sequent formalism, enabling seamless proof exchange between interactive theorem provers and first-order automated theorem provers. We provide a way to represent non-deductive steps—Skolemization, clausification, and Tseitin normal form—as deductive steps within the format. Building upon the existing support in the Lisa proof assistant and the Go\'{e}land theorem prover, SC-TPTP ecosystem is further enhanced with proof output interfaces for Egg and Prover9, as well as proof reconstruction support for HOL Light, Lean, and Rocq.},
booktitle = {Automated Deduction – CADE 30: 30th International Conference on Automated Deduction, Stuttgart, Germany, July 28-31, 2025, Proceedings},
pages = {325–340},
numpages = {16},
location = {Stuttgart, Germany}
}
</pre>
</div>

</details>


### [LastButNotLeast](https://github.com/jcailler/LastButNotLeast/) 🏆

The fastest way to give up — now with 0 bugs! Probably the fastest prover in the competition:
* Runs flawlessly.
* Achieves absolutely nothing.
* 100% success rate in failure.
* Zero proof, infinite potential.
* Proudly earns you a cool CASC T-shirt.

Unfortunately, designing this prover may force you to share a meal with very weird people — but hey, that's the price of true innovation.

The strategy is simple: always return GaveUp. It's fast, reliable, and guarantees we never solve anything — by design.

The prover is expected to come last at [CASC competition](https://tptp.org/CASC/), and any other result would be genuinely surprising — possibly even concerning. In fact, LastButNotLeast proudly exists to ensure that no other prover — no matter how underwhelming — has to carry the burden of being last.

<details>
  <summary>Implementation</summary>

<div>
<pre>
#!/usr/bin/env python

print("% LastButNotLeast: The fastest way to give up!")
print("% For best results, do not expect results.")
print("% SZS status GaveUp")
print("% It's not a bug - it's a philosophical stance.")
print("% Thanks for trying LastButNotLeast :)")
</pre>
</div>

</details>



### [Capex](https://www.docamex.fr/docamex_portail/accueil) 🧀

Capex is a knowledge-based multicriteria decision support tool that structures expert know-how to support technological decision-making in biomass transformation. It was initially applied to French cheese production under AOP/IGP, where preserving and transmitting specialized know-how is critical. By organizing this collective expertise into a structured knowledge base, Capex helps guide practical technological choices and supports the training of technicians and operators.

<details>
  <summary>Please refer to <a href="{{ site.url }}{{ site.baseurl }}/assets/bibtex/docamex.txt"> this paper</a> if you want to cite Capex:</summary>
<div>
<pre>
@misc{Buche2020Capex,
  author       = {Patrice Buche and Julien Cufi and Clément Sipieter and Alrick Oudot and Julie Cailler and Florent Tornil and Julien Couteaux and Sébastien Destercke},
  title        = {Capex, a multicriteria decision support tool for technological recommendations about biomass transformation process based on collective know-how},
  year         = {2020},
  howpublished = {Software directory, swh:1:dir:6da535d0c2ae82f4f1fed1de20633b0edddc162d; origin=https://forgemia.inra.fr/capex/capex-backend-public.git; visit=swh:1:snp:683c16b77efbbdb1ad3d3b185ed8a49e7041b8ac; anchor=swh:1:rev:f2d31640d6487beabb78d7da7b65fe8b4396ed15},
  note         = {HAL no. hal-04957075},
}
</pre>
</div>
</details>