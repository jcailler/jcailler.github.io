---
icon: fas fa-gears
order: 4
---

### [Goéland](https://github.com/GoelandProver/Goeland)



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



### [SC-TPTP Utilities](https://github.com/SC-TPTP/sc-tptp)

Work done in collaboration with [Simon Guilloud](https://simonguilloud.ch/).

SC-TPTP Utilities is a library of tools able to deal with the SC-TPTP format. It includes softwares able to handle, import, export and transform proofs in SC-TPTP format, to add intermediate proof steps, and to export them into Coq. 

<details>
  <summary>Please refer to <a href=""> this paper</a> if you want to cite SC-TPTP utilities:</summary>

<div>
<pre>
@inproceedings{cailler2024sc,
  title={SC-TPTP: An Extension of the TPTP Derivation Format for Sequent-Based Calculus},
  author={Cailler, Julie and Guilloud, Simon},
  booktitle={9th Workshop on Practical Aspects of Automated Reasoning},
  year={2024}
}
</pre>
</div>

</details>