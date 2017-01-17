# regaloebParallax
Parallax avec transform et opacity uniquement.

En modifiant uniquement les éléments <i>transform</i> et <i>opacity</i> des objets parallaxés, on gagne en performance par rapports aux parallax qui modifient les margin, padding, top, left, etc. Alors, c'est mieux.

On détermine les propriétés à animer avec des attributs "data-XXX".<br>
					L'attribut <i>data-x="INITIAL#FINAL"</i> indique que le translateX sera modifiée via la propriété translate3d.<br>
					L'attribut <i>data-y="INITIAL#FINAL"</i> indique que la translateY sera modifiée via la propriété translate3d.<br>
					L'attribut <i>data-scale="INITIAL#FINAL"</i> indique que la scale sera modifiée, INITIAL: scale initiale, FINAL: scale finale.<br>
					L'attribut <i>data-rotate="INITIAL#FINAL"</i> indique que la rotation sera modifiée, INITIAL: rotate initiale, FINAL: rotate finale.<br>
					L'attribut <i>data-skewX="INITIAL#FINAL"</i> indique que le skewX sera modifiée, INITIAL: skewX initiale, FINAL: skewX finale.<br>
					L'attribut <i>data-skewY="INITIAL#FINAL"</i> indique que le skewY sera modifiée, INITIAL: skewY initiale, FINAL: skewY finale.<br>
					L'attribut <i>data-o="INITIAL#FINAL"</i> indique que l'opacité sera modifiée.<br>
					L'attribut <i>data-end="NUM"</i> indique à quel endroit du viewport l'objet atteint ses valeurs finales : 2 = au milieu, 3 = au 2/3, 1 au scroll 0. Valeur par défaut: 2.<br><br>
					Lorsque l'élément arrive dans le viewport, la propriété prend la valeur INITIAL<br>
					À l'endroit du viewport déterminé par data-end (au milieu par défaut), la propriété prend la valeur FINAL.

Explications et exemples : http://www.regaloeb.com/pages/diaporamas-wiz/regaloebParallax.html
