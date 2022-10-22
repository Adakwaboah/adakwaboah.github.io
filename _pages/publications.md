---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
* **Akwaboah, A.** and Etienne-Cummings, R., 2022, July. LODeNNS: A Linearly-approximated and Optimized Dendrocentric Nearest Neighbor STDP. In Proceedings of the International Conference on Neuromorphic Systems 2022 (pp. 1-8). https://doi.org/10.1145/3546790.3546793

* Ghaffari, D.H., **Akwaboah, A.D.**, Mirzakhalili, E. and Weiland, J.D., 2021. Real-Time Optimization of Retinal Ganglion Cell Spatial Activity in Response to Epiretinal Stimulation. IEEE Transactions on Neural Systems and Rehabilitation Engineering, 29, pp.2733-2741. https://doi.org/10.1109/TNSRE.2021.3138297
    
* **Akwaboah, A.D.**, Tsevi, B., Yamlome, P., Treat, J.A., Brucal-Hallare, M., Cordeiro, J.M. and Deo, M., 2021. An in silico hiPSC-Derived Cardiomyocyte Model Built With Genetic Algorithm. Frontiers in Physiology, p.778. https://doi.org/10.3389/fphys.2021.675867
    
* Tsevi, B., **Akwaboah, A.D.**, Treat, J.A., Goodrow, R., Lam, V., Owusu-Mensah, A., Audette, M., Cordeiro, J.M. and Deo, M., 2021. Investigating Arrhythmogenic Potential of a Novel KCNH2 Mutation Leading to Long QT Syndrome. Circulation, 144(Suppl_1), pp.A12269-A12269. https://doi.org/10.1161/circ.144.suppl_1.12269
    
* Deo, M., **Akwaboah, A.**, Tsevi, B., Treat, J.A. and Cordeiro, J.M., 2020. Role of the rapid delayed rectifier K+ current in human induced pluripotent stem cells derived cardiomyocytes. Archives of stem cell and therapy, 1(1), p.14. https://doi.org/10.46439/stemcell.1.003
    
**Akwaboah, A.D.**, Yamlome, P., Treat, J.A., Cordeiro, J.M. and Deo, M., 2020, July. Genetic algorithm for fitting cardiac cell biophysical model formulations. In 2020 42nd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC) (pp. 2463-2466). IEEE. https://doi.org/10.1109/EMBC44109.2020.9175707
    
Yamlome, P., **Akwaboah, A.D.**, Marz, A. and Deo, M., 2020, July. Convolutional neural network based breast cancer histopathology image classification. In 2020 42nd Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC) (pp. 1144-1147). IEEE. https://doi.org/10.1109/EMBC44109.2020.9176594

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
