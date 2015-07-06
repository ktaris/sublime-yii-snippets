YiiSnippets
===

The YiiSnippets package contains snippets used when developing with the Yii and Yii2 framework, and are part of what we at Ktaris find ourselves writing again, and again, and again.



Snippets Available for PHP
---



**&lt;?**

Prints: `<?= \$$1 ?>`

**dbl** (stands for *document block link*)

Prints: `\{@link ${1:$SELECTION}\}`



Snippets Available Common for Yii 1.\* 2.\*
---



**yiit**
Prints: `Yii::t('${2:app}', '${1:$SELECTION}')`. It can be accesed using keys *Ctrl + k, t*, and applied to the selected text.

**yiite**
Prints: `<?= Yii::t('${2:app}', '${1:$SELECTION}') ?>`



Snippets Available for Yii 2.\*
---



**yii2a**

Prints: `Yii::\$app->$1`



Snippets Available for Yii 1.\*
---



**yii1a**

Prints: `Yii::app()->$1`

**yii1e**

Prints: `Yii::app()->end();`

**yii1f**

Prints: `Yii::app()->user->setFlash('${1:success}', '$2')${3:;}`

**yii1p**

Prints: `Yii::app()->params['$1']`



Key bindings (for Windows)
---



 + [*Ctrl + k, t*] for **yiit**
 + [*Ctrl + k, l*] for **dbl**