# geonamesjp_vs_geonames
[GeoNames.jp](http://geonames.jp/) と[GeoNames.org](http://www.geonames.org/) のリンクセット


## What's this?
GeoNames.jp と GeoNames.org を owl:sameAs で結ぶリンクセットです。
この関連性によって、 GeoNames.jp の URI と GeoNames.org の URI の相互運用性が確保されます。

このリンクセットは  [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) で公開しています。


## Example

	@prefix owl:   <http://www.w3.org/2002/07/owl#> .
	@prefix gnjp:  <http://geonames.jp/resource/> .

	gnjp:北海道  owl:sameAs  <http://sws.geonames.org/2130037/> .
	gnjp:北海道三笠市  owl:sameAs  <http://sws.geonames.org/8301405/> .
	gnjp:北海道上川郡  owl:sameAs  <http://sws.geonames.org/2129758/> .
	gnjp:北海道上川郡上川町  owl:sameAs  <http://sws.geonames.org/2129759/> .
	gnjp:北海道上川郡下川町  owl:sameAs  <http://sws.geonames.org/2128138/> .
	gnjp:北海道上川郡剣淵町  owl:sameAs  <http://sws.geonames.org/7429534/> .
	gnjp:北海道上川郡和寒町  owl:sameAs  <http://sws.geonames.org/2127499/> .
	
## Note
* [GeoTree](http://geotree.geonames.org/) の **アジア** ＞ **日本** 配下にある、都道府県郡市区町村を対象としています






