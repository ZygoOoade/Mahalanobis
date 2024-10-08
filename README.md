# Mahalanobis distance

Soit $`\mu`$ la moyenne d'une distribution.

Soit $`\rho`$ le coefficient de corrélation, qui indique à quel point deux variables sont corrélées. Il s’agit d’une valeur normalisée de la covariance. Plus la corrélation est forte, plus les éléments non diagonaux de \mathbit{C} sont élevés, plus ρ est proche de ± 1, plus $`ρ^2`$ sera proche de 0 et plus det(\mathbit{C}) sera petit.

Plutôt que de mesurer la distance entre $`\mu`$ et un point _x_ , la distance de mahalanobis prend en compte la distribution de manière à savoir si le point est probable étant donné cette distribution. $`\frac{x_1-\mu_1}{\sigma_1\ }`$ et $`\frac{x_2-\mu_2}{\sigma_2}`$ représentent des formes standardisées pour $`x_1`$ et $`x_2`$. Le terme  $`\rho\left(\frac{x_1-\mu_1}{\sigma_1\ }\right)`$ reflète la valeur attendue de $`x_2`$ étant donnée la corrélation $`\rho`$. Si cette différence est 0, $`x_2`$ suit parfaitement la droite de corrélation.

