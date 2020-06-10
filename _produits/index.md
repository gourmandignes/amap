---
layout: default
title: Liste des catégories de produits de l'amap

---


<section id="ghTree" class="ghTree" data-title="tree">
    <header>
        <h1>Catégories des produits distribués par Gourmandignes</h1>
    </header>
    <div class="table">
        <!--{% assign cat = site[page.collection] | map: 'categorie' | uniq %}
        {{ cat | jsonify }}
        <ul>
          {% for tag in cat %}{% unless tag == nil %}
            <li><a href="index.html#{{ tag }}">{{ tag }}</a></li>
            {% endunless %}{% endfor %}
        </ul>
        -->

  <div class="grille">
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../boissons">Boissons</a>
        </div>
        <div>
            <a href="../boissons">
                <img src="./media/boissons.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../cremerie">Crèmerie</a>
        </div>
        <div>
            <a href="../cremerie">
                <img src="./media/cremerie.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../epicerie">Épicerie</a>
        </div>
        <div>
            <a href="../epicerie">
                <img src="./media/epicerie.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../legumes">Fruits & Légumes</a>
        </div>
        <div>
            <a href="../legumes">
                <img src="./media/legumes.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../viandes">Viandes</a>
        </div>
        <div>
            <a href="../viandes">
                <img src="./media/viandes.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../boulangerie">Boulangerie & Pâtisserie</a>
        </div>
        <div>
            <a href="../boulangerie">
                <img src="./media/boulangerie.jpg" width="260">
            </a>
        </div>
    </div>
    <div class="colonne">
        <div>
                <a class="ghTreeReadmore" href="../maison">Maison & Jardin</a>
        </div>
        <div>
            <a href="../maison">
                <img src="./media/maison.jpg" width="260">
            </a>
        </div>
    </div>
</div>
</section>