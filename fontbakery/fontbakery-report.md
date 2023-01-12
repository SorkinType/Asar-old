## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[20] Asar-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "Licenced under the SIL Open Font License, Version 1.1, available with a FAQ at: https://scripts.sil.org/OFL" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright (c) 2021 by Eben Sorkin" [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.0019989013671875 is less than version on Google Fonts (1.0030059814453125).
* 🔥 **FAIL** Version number 1.0019989013671875 is less than version on Google Fonts GitHub repo (1.0030059814453125).
</div></details><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** fsSelection bit 7 needs to be enabled because the family on Google Fonts has it enabled. [code: bad-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Asar-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Name table records must not have trailing spaces. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/name/trailing_spaces">com.google.fonts/check/name/trailing_spaces</a>)</summary><div>


* 🔥 **FAIL** Name table record with key = (3, 1, 1033, 14) has trailing spaces that must be removed: ' http://sc[...]il.org/OFL' [code: trailing-space]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1390, but got 1196 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotbelowcomb

	- gravecomb

	- hookabovecomb

	- tildecomb

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni030F

	- uni0311

	- uni0312

	- uni0326

	- uni0327

	- uni0328

	- uni032E

	- uni032F

	- uni0900

	- uni0901

	- uni0902

	- uni093A

	- uni093C

	- uni0941

	- uni0942

	- uni0943

	- uni0944

	- uni0945

	- uni0946

	- uni0947

	- uni0948

	- uni094D

	- uni0951

	- uni0952

	- uni0953

	- uni0954

	- uni0956

	- uni0957

	- uni0962 

	- And uni0963 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'uni02BA', 'component': 'minute', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x01F8 (LATIN CAPITAL LETTER N WITH GRAVE)


	- 0x01F9 (LATIN SMALL LETTER N WITH GRAVE)


	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)
 

	- And 0x1D3A (MODIFIER LETTER CAPITAL N)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* OE
	* braceright
	* dv_CRa
	* dv_DdhDdhYa
	* dv_K.half
	* dv_KRa
	* dv_KSs.half
	* dv_KhVa
	* dv_MatraAiReph
	* dv_MatraAiRephCandraBindu
	* dv_Ng.half
	* dv_Q.half
	* dv_QRa
	* dv_SsRa
	* f_f_i
	* parenright
	* uni091E and uni2074
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- I.uc

	- acute.cap

	- b_bh_radeva

	- b_dh_vadeva

	- ba_radeva

	- bh_nadeva

	- bh_radeva

	- bh_rakar_yadeva

	- bh_vadeva

	- bh_yadeva

	- bha_radeva

	- c_ch_vadeva

	- ca_radeva

	- caron.cap

	- caronvertical

	- ch_nadeva

	- ch_vadeva

	- ch_yadeva

	- d_bh_yadeva

	- d_dh_yadeva

	- d_rakar_yadeva

	- da_rVocalicMatradeva

	- da_radeva

	- dd_dd_yadeva

	- dd_ddadeva

	- dd_ddhadeva

	- dd_ghadeva

	- dd_madeva

	- dd_nadeva

	- dd_ttadeva

	- dd_yadeva

	- dda_radeva

	- ddh_ddh_yadeva

	- ddh_ddhadeva

	- ddh_nadeva

	- ddh_yadeva

	- dh_madeva

	- dh_n_yadeva

	- dh_nadeva

	- dh_radeva

	- dh_vadeva

	- dh_yadeva

	- dha_radeva

	- dieresis.cap

	- dv_B.half

	- dv_BBa

	- dv_BBhRa

	- dv_BBha

	- dv_BDa

	- dv_BDhVa

	- dv_BDha

	- dv_BJYa

	- dv_BJa

	- dv_BJha

	- dv_BJha.NEP

	- dv_BLYa

	- dv_BLa

	- dv_BLa.MAR

	- dv_BNa

	- dv_BRa

	- dv_BSa

	- dv_BSha

	- dv_BTa

	- dv_BVa

	- dv_BYa

	- dv_BZa

	- dv_Bb.half

	- dv_Bh.half

	- dv_BhBha

	- dv_BhCha

	- dv_BhDda

	- dv_BhDha

	- dv_BhHa

	- dv_BhLa

	- dv_BhLa.MAR

	- dv_BhNa

	- dv_BhNga

	- dv_BhNya

	- dv_BhR.half

	- dv_BhRYa

	- dv_BhRa

	- dv_BhSha

	- dv_BhTha

	- dv_BhVa

	- dv_BhYa

	- dv_BoldJha

	- dv_C.half

	- dv_CBha

	- dv_CCYa

	- dv_CCa

	- dv_CChVa

	- dv_CCha

	- dv_CDda

	- dv_CDha

	- dv_CHa

	- dv_CJNya

	- dv_CJha

	- dv_CMa

	- dv_CNa

	- dv_CRa

	- dv_CSha

	- dv_CTha

	- dv_CYa

	- dv_Ch.half

	- dv_ChRYa

	- dv_ChRa

	- dv_ChRaMatraU

	- dv_ChRaMatraUu

	- dv_ChVa

	- dv_ChYa

	- dv_ColdJha

	- dv_D.half

	- dv_DBRa

	- dv_DBa

	- dv_DDYa

	- dv_DDa

	- dv_DGRa

	- dv_DGa

	- dv_DMa

	- dv_DMatraU

	- dv_DMatraUu

	- dv_DMatraVocalicR

	- dv_DNa

	- dv_DR.half

	- dv_DRYa

	- dv_DRa

	- dv_DRaMatraU

	- dv_DRaMatraUu

	- dv_DVRa

	- dv_DVYa

	- dv_DVa

	- dv_DYa

	- dv_Dd.half

	- dv_DdDdYa

	- dv_DdDda

	- dv_DdDdha

	- dv_DdRa

	- dv_DdRaMatraU

	- dv_DdRaMatraUu

	- dv_DdTta

	- dv_DdYa

	- dv_Ddh.half

	- dv_DdhDdhYa

	- dv_DdhDdha

	- dv_DdhRYa

	- dv_DdhRa

	- dv_DdhRaMatraU

	- dv_DdhRaMatraUu

	- dv_DdhYa

	- dv_Dh.half

	- dv_DhBha

	- dv_DhCa

	- dv_DhCha

	- dv_DhDda

	- dv_DhDha

	- dv_DhHa

	- dv_DhMa

	- dv_DhNYa

	- dv_DhNa

	- dv_DhNga

	- dv_DhR.half

	- dv_DhRa

	- dv_DhSha

	- dv_DhTha

	- dv_DhVa

	- dv_DhYa

	- dv_F.half

	- dv_FFa

	- dv_FRa

	- dv_FSa

	- dv_FTa

	- dv_FZa

	- dv_GBhYa

	- dv_GDhVa

	- dv_GDhYa

	- dv_GNYa

	- dv_GNa

	- dv_GR.half

	- dv_GRYa

	- dv_Gh.half

	- dv_GhBha

	- dv_GhCa

	- dv_GhCha

	- dv_GhDa

	- dv_GhDda

	- dv_GhDha

	- dv_GhHa

	- dv_GhJNya

	- dv_GhMa

	- dv_GhNa

	- dv_GhNga

	- dv_GhR.half

	- dv_GhRa

	- dv_GhSha

	- dv_GhTha

	- dv_GhYa

	- dv_Ghh.half

	- dv_GhhRa

	- dv_H.half

	- dv_HLa

	- dv_HLa.MAR

	- dv_HM.half

	- dv_HMYa

	- dv_HMa

	- dv_HMatraU

	- dv_HMatraUu

	- dv_HMatraVocalicR

	- dv_HNa

	- dv_HRa

	- dv_HVa

	- dv_HYa

	- dv_IiAnusvara

	- dv_JBa

	- dv_JBha

	- dv_JDa

	- dv_JDda

	- dv_JDdha

	- dv_JGa

	- dv_JJ.half

	- dv_JJNya

	- dv_JJVa

	- dv_JJYa

	- dv_JJa

	- dv_JJha

	- dv_JJna

	- dv_JKa

	- dv_JKha

	- dv_JMa

	- dv_JNa

	- dv_JNy.half

	- dv_JNyYa

	- dv_JNya

	- dv_JRa

	- dv_JSa

	- dv_JTa

	- dv_JTha

	- dv_JTta

	- dv_JTtha

	- dv_JVa

	- dv_JYa

	- dv_Jh.half

	- dv_Jh.half.NEP

	- dv_JhBha

	- dv_JhCha

	- dv_JhDda

	- dv_JhDha

	- dv_JhHa

	- dv_JhMa

	- dv_JhNa

	- dv_JhNga

	- dv_JhRa

	- dv_JhSha

	- dv_JhYa

	- dv_Jha.NEP

	- dv_Jj.half

	- dv_KBha

	- dv_KCa

	- dv_KCha

	- dv_KDa

	- dv_KDda

	- dv_KDha

	- dv_KGha

	- dv_KHa

	- dv_KJNya

	- dv_KJa

	- dv_KJha

	- dv_KKYa

	- dv_KKa

	- dv_KKha

	- dv_KLa

	- dv_KLa.MAR

	- dv_KMa

	- dv_KNa

	- dv_KNga

	- dv_KNna

	- dv_KNya

	- dv_KPRa

	- dv_KPa

	- dv_KPha

	- dv_KR.half

	- dv_KRa

	- dv_KRa.NEP

	- dv_KS.half

	- dv_KSDda

	- dv_KSPLa

	- dv_KSPLa.MAR

	- dv_KSPRa

	- dv_KSTa

	- dv_KSTta

	- dv_KSa

	- dv_KSha

	- dv_KSs.half

	- dv_KSsM.half

	- dv_KSsMYa

	- dv_KSsMa

	- dv_KSsRa

	- dv_KSsVa

	- dv_KSsYa

	- dv_KSsa

	- dv_KTRa

	- dv_KTRa.alt

	- dv_KTVa

	- dv_KTYa

	- dv_KTa

	- dv_KTha

	- dv_KTta

	- dv_KVYa

	- dv_KVa

	- dv_KYa

	- dv_KhKha

	- dv_KhMa

	- dv_KhNa

	- dv_KhSha

	- dv_KhTa

	- dv_KhVa

	- dv_KhYa

	- dv_Khh.half

	- dv_KhhMa

	- dv_KhhRa

	- dv_KhhSa

	- dv_KhhSha

	- dv_KhhTa

	- dv_KhhVa

	- dv_KhhYa

	- dv_KoldJha

	- dv_L.half

	- dv_LBa

	- dv_LBh.half

	- dv_LBha

	- dv_LCa

	- dv_LDRa

	- dv_LDa

	- dv_LDda

	- dv_LDdha

	- dv_LDha

	- dv_LGa

	- dv_LGha

	- dv_LHYa

	- dv_LHa

	- dv_LJa

	- dv_LKYa

	- dv_LKa

	- dv_LKha

	- dv_LLYa

	- dv_LLa

	- dv_LLa.MAR

	- dv_LMa

	- dv_LNa

	- dv_LNya

	- dv_LPa

	- dv_LPha

	- dv_LRa

	- dv_LSa

	- dv_LSha

	- dv_LTa

	- dv_LThYa

	- dv_LTha

	- dv_LTta

	- dv_LTtha

	- dv_LVDda

	- dv_LVa

	- dv_LYa

	- dv_LZa

	- dv_La.MAR

	- dv_LlYa

	- dv_Lll.half

	- dv_M.half

	- dv_MBRa

	- dv_MBYa

	- dv_MBa

	- dv_MBh.half

	- dv_MBhRa

	- dv_MBhVa

	- dv_MBhYa

	- dv_MBha

	- dv_MCa

	- dv_MCha

	- dv_MDa

	- dv_MDda

	- dv_MDha

	- dv_MHa

	- dv_MJha

	- dv_MLa

	- dv_MLa.MAR

	- dv_MMa

	- dv_MNa

	- dv_MNga

	- dv_MNya

	- dv_MPRa

	- dv_MPa

	- dv_MRa

	- dv_MSa

	- dv_MSha

	- dv_MTa

	- dv_MTha

	- dv_MVa

	- dv_MYa

	- dv_MatraAaAnusvara

	- dv_MatraAaCandraBindu

	- dv_MatraAaReph

	- dv_MatraAaRephAnusvara

	- dv_MatraAiAnusvara

	- dv_MatraAiCandraBindu

	- dv_MatraAiReph

	- dv_MatraAiRephAnusvara

	- dv_MatraAiRephCandraBindu

	- dv_MatraAuAnusvara

	- dv_MatraAuCandraBindu

	- dv_MatraAuReph

	- dv_MatraAuRephAnusvara

	- dv_MatraAuRephCandraBindu

	- dv_MatraAwAnusvara

	- dv_MatraAwCandraBindu

	- dv_MatraAwReph

	- dv_MatraAwRephAnusvara

	- dv_MatraAwRephCandraBindu

	- dv_MatraCandraEAnusvara

	- dv_MatraCandraECandraBindu

	- dv_MatraCandraEReph

	- dv_MatraCandraERephAnusvara

	- dv_MatraCandraOAnusvara

	- dv_MatraCandraOCandraBindu

	- dv_MatraCandraOReph

	- dv_MatraCandraORephAnusvara

	- dv_MatraCandraORephCandraBindu

	- dv_MatraEAnusvara

	- dv_MatraEReph

	- dv_MatraERephAnusvara

	- dv_MatraIAnusvara

	- dv_MatraIAnusvara.1

	- dv_MatraIAnusvara.2

	- dv_MatraIAnusvara.3

	- dv_MatraIAnusvara.4

	- dv_MatraICandraBindu

	- dv_MatraICandraBindu.1

	- dv_MatraICandraBindu.2

	- dv_MatraICandraBindu.3

	- dv_MatraICandraBindu.4

	- dv_MatraIReph

	- dv_MatraIReph.1

	- dv_MatraIReph.2

	- dv_MatraIReph.3

	- dv_MatraIReph.4

	- dv_MatraIRephAnusvara

	- dv_MatraIRephAnusvara.1

	- dv_MatraIRephAnusvara.2

	- dv_MatraIRephAnusvara.3

	- dv_MatraIRephAnusvara.4

	- dv_MatraIRephCandraBindu

	- dv_MatraIRephCandraBindu.1

	- dv_MatraIRephCandraBindu.2

	- dv_MatraIRephCandraBindu.3

	- dv_MatraIRephCandraBindu.4

	- dv_MatraIi.1

	- dv_MatraIi.2

	- dv_MatraIiAnusvara

	- dv_MatraIiAnusvara.1

	- dv_MatraIiAnusvara.2

	- dv_MatraIiCandraBindu

	- dv_MatraIiCandraBindu.1

	- dv_MatraIiCandraBindu.2

	- dv_MatraIiReph

	- dv_MatraIiReph.1

	- dv_MatraIiReph.2

	- dv_MatraIiRephAnusvara

	- dv_MatraIiRephAnusvara.1

	- dv_MatraIiRephAnusvara.2

	- dv_MatraIiRephCandraBindu

	- dv_MatraIiRephCandraBindu.1

	- dv_MatraIiRephCandraBindu.2

	- dv_MatraOAnusvara

	- dv_MatraOCandraBindu

	- dv_MatraOReph

	- dv_MatraORephAnusvara

	- dv_MatraORephCandraBindu

	- dv_MatraShortEAnusvara

	- dv_MatraShortEReph

	- dv_MatraShortOAnusvara

	- dv_MatraShortOCandraBindu

	- dv_MatraShortOReph

	- dv_MatraShortORephAnusvara

	- dv_MatraShortORephCandraBindu

	- dv_NBh.half

	- dv_NBhVa

	- dv_NBhYa

	- dv_NBha

	- dv_NCa

	- dv_NCha

	- dv_NDRa

	- dv_NDVa

	- dv_NDa

	- dv_NDda

	- dv_NDhRa

	- dv_NDhVa

	- dv_NDhYa

	- dv_NDha

	- dv_NGa

	- dv_NHYa

	- dv_NHa

	- dv_NJYa

	- dv_NKSa

	- dv_NKa

	- dv_NMYa

	- dv_NMa

	- dv_NN.half

	- dv_NNYa

	- dv_NNa

	- dv_NNya

	- dv_NPRa

	- dv_NPa

	- dv_NPha

	- dv_NS.half

	- dv_NSMYa

	- dv_NSTta

	- dv_NSYa

	- dv_NSa

	- dv_NSha

	- dv_NTRa

	- dv_NTRa.alt

	- dv_NTSa

	- dv_NTYa

	- dv_NTa

	- dv_NThVa

	- dv_NThYa

	- dv_NTha

	- dv_NTta

	- dv_NVa

	- dv_NYa

	- dv_Na.post

	- dv_Ng.half

	- dv_NgRa

	- dv_NgRaMatraU

	- dv_NgRaMatraUu

	- dv_NgYa

	- dv_Nn.half

	- dv_NnRa

	- dv_Nnn.half

	- dv_NnnRa

	- dv_Ny.half

	- dv_NyBha

	- dv_NyCYa

	- dv_NyCa

	- dv_NyCha

	- dv_NyDda

	- dv_NyHa

	- dv_NyJNya

	- dv_NyJYa

	- dv_NyJa

	- dv_NyNga

	- dv_NyRa

	- dv_NySha

	- dv_P.half

	- dv_PBha

	- dv_PCha

	- dv_PDda

	- dv_PDha

	- dv_PLa

	- dv_PLa.MAR

	- dv_PMa

	- dv_PNa

	- dv_PNga

	- dv_PPa

	- dv_PPha

	- dv_PR.half

	- dv_PRa

	- dv_PSa

	- dv_PSha

	- dv_PTYa

	- dv_PTa

	- dv_PTha

	- dv_PTtYa

	- dv_PTta

	- dv_PTthYa

	- dv_PTtha

	- dv_PVa

	- dv_PYa

	- dv_PhBha

	- dv_PhCa

	- dv_PhCha

	- dv_PhDda

	- dv_PhDha

	- dv_PhGa

	- dv_PhGha

	- dv_PhHa

	- dv_PhJNya

	- dv_PhJa

	- dv_PhJha

	- dv_PhLa

	- dv_PhLa.MAR

	- dv_PhNa

	- dv_PhNga

	- dv_PhNya

	- dv_PhPa

	- dv_PhPha

	- dv_PhSha

	- dv_PhTa

	- dv_PhTha

	- dv_PhTta

	- dv_PhYa

	- dv_PholdJha

	- dv_Q.half

	- dv_QBa

	- dv_QFa

	- dv_QMa

	- dv_QPha

	- dv_QQa

	- dv_QRa

	- dv_QTa

	- dv_RMatraU

	- dv_RMatraUu

	- dv_Ra.post

	- dv_Reph

	- dv_RephAnusvara

	- dv_RephCandraBindu

	- dv_Rr.half

	- dv_S.half

	- dv_SBa

	- dv_SCha

	- dv_SDa

	- dv_SJa

	- dv_SKRa

	- dv_SKRa.NEP

	- dv_SKVa

	- dv_SKa

	- dv_SKha

	- dv_SLa

	- dv_SLa.MAR

	- dv_SMYa

	- dv_SMa

	- dv_SNYa

	- dv_SNa

	- dv_SPRa

	- dv_SPa

	- dv_SPha

	- dv_SR.half

	- dv_SRa

	- dv_SSa

	- dv_STRa

	- dv_STRa.alt

	- dv_STVa

	- dv_STYa

	- dv_STa

	- dv_SThYa

	- dv_STha

	- dv_STta

	- dv_SVa

	- dv_SYa

	- dv_Sh.half.MAR

	- dv_ShMatraVocalicR

	- dv_ShR.half

	- dv_ShRYa

	- dv_ShRa

	- dv_Sha.MAR

	- dv_ShrNa

	- dv_Ss.half

	- dv_SsKRa

	- dv_SsKa

	- dv_SsKra.NEP

	- dv_SsMYa

	- dv_SsMa

	- dv_SsNnYa

	- dv_SsNna

	- dv_SsPRa

	- dv_SsPa

	- dv_SsPha

	- dv_SsR.half

	- dv_SsRa

	- dv_SsSsa

	- dv_SsTtVa

	- dv_SsTtYa

	- dv_SsTta

	- dv_SsTthYa

	- dv_SsTtha

	- dv_SsVa

	- dv_SsYa

	- dv_T.half

	- dv_TBha

	- dv_TCa

	- dv_TDa

	- dv_TDha

	- dv_THa

	- dv_TJa

	- dv_TKRa

	- dv_TKRa.NEP

	- dv_TKSsa

	- dv_TKVa

	- dv_TKYa

	- dv_TKa

	- dv_TKhNa

	- dv_TKhRa

	- dv_TKha

	- dv_TLa

	- dv_TLa.MAR

	- dv_TMYa

	- dv_TMa

	- dv_TNYa

	- dv_TNa

	- dv_TNya

	- dv_TPLa

	- dv_TPLa.MAR

	- dv_TPRa

	- dv_TPa

	- dv_TPha

	- dv_TR.half

	- dv_TR.half.alt

	- dv_TRYa

	- dv_TRYa.alt

	- dv_TRa

	- dv_TRa.alt

	- dv_TS.half

	- dv_TSNYa

	- dv_TSNa

	- dv_TSVa

	- dv_TSYa

	- dv_TSa

	- dv_TT.half

	- dv_TTVa

	- dv_TTYa

	- dv_TTa

	- dv_TTha

	- dv_TTta

	- dv_TTtha

	- dv_TVa

	- dv_TYa

	- dv_Th.half

	- dv_ThBha

	- dv_ThCa

	- dv_ThCha

	- dv_ThDda

	- dv_ThDha

	- dv_ThGha

	- dv_ThHa

	- dv_ThNa

	- dv_ThNga

	- dv_ThR.half

	- dv_ThRa

	- dv_ThSha

	- dv_ThTha

	- dv_ThVa

	- dv_ThYa

	- dv_Tt.half

	- dv_TtDdha

	- dv_TtRa

	- dv_TtRaMatraU

	- dv_TtRaMatraUu

	- dv_TtTtYa

	- dv_TtTta

	- dv_TtTtha

	- dv_TtVa

	- dv_TtYa

	- dv_Tth.half

	- dv_TthRa

	- dv_TthRaMatraU

	- dv_TthRaMatraUu

	- dv_TthTthYa

	- dv_TthTtha

	- dv_TthYa

	- dv_V.half

	- dv_VHa

	- dv_VLa

	- dv_VLa.MAR

	- dv_VNa

	- dv_VR.half

	- dv_VRa

	- dv_VVa

	- dv_VYa

	- dv_YBha

	- dv_YCha

	- dv_YDda

	- dv_YDha

	- dv_YGha

	- dv_YNa

	- dv_YNga

	- dv_YSha

	- dv_YTha

	- dv_YYa

	- dv_Ya.post

	- dv_Yy.half

	- dv_YyRa

	- dv_Z.half

	- dv_ZRa

	- dv_ZYa

	- dv_ZZa

	- dv_oldJha

	- eight.dnom

	- eight.numr

	- five.dnom

	- five.numr

	- four.dnom

	- four.numr

	- g_bh_yadeva

	- g_dh_vadeva

	- g_dh_yadeva

	- g_rakar_yadeva

	- ga_radeva

	- gh_madeva

	- gh_nadeva

	- gh_radeva

	- gh_yadeva

	- gha_radeva

	- ghh_radeva

	- gravecomb.case

	- ha_rVocalicMatradeva

	- hookabovecomb.case

	- hungarumlaut.cap

	- i.cy

	- i.dot

	- j_ny_yadeva

	- ja_radeva

	- jh_madeva

	- jh_nadeva

	- jh_radeva

	- jh_yadeva

	- jha_radeva

	- k_ss_madeva

	- k_ss_radeva

	- k_ss_vadeva

	- k_ss_yadeva

	- ka_radeva

	- kh_khadeva

	- kh_madeva

	- kh_nadeva

	- kh_radeva

	- kh_shadeva

	- kh_tadeva

	- kh_vadeva

	- kh_yadeva

	- kha_radeva

	- khh_madeva

	- khh_radeva

	- khh_sadeva

	- khh_shadeva

	- khh_tadeva

	- khh_vadeva

	- khh_yadeva

	- l_th_yadeva

	- la_radeva

	- ll_yadeva

	- m_bh_radeva

	- ma_radeva

	- macron.cap

	- n_dh_radeva

	- n_dh_vadeva

	- n_dh_yadeva

	- n_th_vadeva

	- n_th_yadeva

	- na_radeva

	- ng_g_radeva

	- ng_gadeva

	- ng_gh_radeva

	- ng_ghadeva

	- ng_k_radeva

	- ng_k_ssadeva

	- ng_k_t_tadeva

	- ng_kadeva

	- ng_khadeva

	- ng_madeva

	- ng_yadeva

	- nine.dnom

	- nine.numr

	- nn_ddadeva

	- nn_ddhadeva

	- nn_madeva

	- nn_nnadeva

	- nn_radeva

	- nn_ttadeva

	- nn_tthadeva

	- nn_vadeva

	- nn_yadeva

	- nna_radeva

	- ny_c_yadeva

	- ny_cadeva

	- ny_chadeva

	- ny_j_yadeva

	- ny_jadeva

	- ny_radeva

	- ny_shadeva

	- one.dnom

	- one.numr

	- pa_radeva

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

	- ph_jadeva

	- ph_ladeva

	- ph_nadeva

	- ph_padeva

	- ph_phadeva

	- ph_radeva

	- ph_shadeva

	- ph_tadeva

	- ph_ttadeva

	- ph_yadeva

	- pha_radeva

	- ra_uMatradeva

	- ra_uuMatradeva

	- ring.cap

	- ring_acutecomb

	- rr_hadeva

	- rr_yadeva

	- s_th_yadeva

	- sa_radeva

	- seven.dnom

	- seven.numr

	- sh_cadeva

	- sh_chadeva

	- sh_kadeva

	- sh_ladeva

	- sh_madeva

	- sh_nadeva

	- sh_qadeva

	- sh_radeva

	- sh_rakar_yadeva

	- sh_shadeva

	- sh_tadeva

	- sh_ttadeva

	- sh_vadeva

	- sh_yadeva

	- sha_radeva

	- six.dnom

	- six.numr

	- ss_k_radeva

	- ss_kadeva

	- ss_m_yadeva

	- ss_madeva

	- ss_nn_yadeva

	- ss_nnadeva

	- ss_p_radeva

	- ss_padeva

	- ss_phadeva

	- ss_ssadeva

	- ss_tt_rakardeva

	- ss_tt_vadeva

	- ss_tt_yadeva

	- ss_ttadeva

	- ss_tth_rakardeva

	- ss_tth_yadeva

	- ss_tthadeva

	- ss_vadeva

	- ss_yadeva

	- t_kh_nadeva

	- t_kh_radeva

	- t_rakar_yadeva

	- ta_radeva

	- th_nadeva

	- th_radeva

	- th_vadeva

	- th_yadeva

	- tha_radeva

	- three.dnom

	- three.numr

	- tilde.cap

	- tildecomb.case

	- tildecomb_acutecomb

	- tildecomb_acutecomb.case

	- tt_ddhadeva

	- tt_nadeva

	- tt_sadeva

	- tt_tt_yadeva

	- tt_ttadeva

	- tt_tthadeva

	- tt_vadeva

	- tt_yadeva

	- tta_radeva

	- tth_nadeva

	- tth_tth_yadeva

	- tth_tthadeva

	- tth_yadeva

	- ttha_radeva

	- two.dnom

	- two.numr

	- uni0062006A092F

	- uni0062006C092F

	- uni0062091C

	- uni00620924

	- uni00620926

	- uni00620927

	- uni00620928

	- uni0062092C

	- uni0062092D

	- uni0062092F

	- uni00620930

	- uni00620932

	- uni00620935

	- uni00620936

	- uni00620938

	- uni0062095B

	- uni0063091A

	- uni0063091B

	- uni00630928

	- uni0063092E

	- uni0063092F

	- uni00630930

	- uni006400620930

	- uni00640064092F

	- uni006400670930

	- uni00640076092F

	- uni006400760930

	- uni00640917

	- uni00640918

	- uni00640926

	- uni00640927

	- uni00640928

	- uni0064092C

	- uni0064092D

	- uni0064092E

	- uni0064092F

	- uni00640930

	- uni00640935

	- uni00660924

	- uni00660930

	- uni00660938

	- uni0066095B

	- uni0066095E

	- uni0067006E092F

	- uni00670917

	- uni00670918

	- uni0067091C

	- uni00670923

	- uni00670926

	- uni00670927

	- uni00670928

	- uni0067092C

	- uni0067092D

	- uni0067092E

	- uni0067092F

	- uni00670930

	- uni00670932

	- uni00670935

	- uni00670938

	- uni0068006D092F

	- uni00680923

	- uni00680928

	- uni0068092E

	- uni0068092F

	- uni00680930

	- uni00680932

	- uni00680935

	- uni006A006A091E

	- uni006A006A092F

	- uni006A006A0935

	- uni006A0915

	- uni006A091C

	- uni006A091D

	- uni006A091E

	- uni006A091E094D

	- uni006A091F

	- uni006A0921

	- uni006A0924

	- uni006A0926

	- uni006A0928

	- uni006A092C

	- uni006A092E

	- uni006A092F

	- uni006A0930

	- uni006A0935

	- uni006B00700930

	- uni006B007300700930

	- uni006B007300700932

	- uni006B0073091F

	- uni006B00730921

	- uni006B00730924

	- uni006B0073092A

	- uni006B00740924

	- uni006B0074092F

	- uni006B00740930

	- uni006B00740935

	- uni006B0076092F

	- uni006B0915

	- uni006B0916

	- uni006B091A

	- uni006B091C

	- uni006B091F

	- uni006B0923

	- uni006B0924

	- uni006B0924094D

	- uni006B0925

	- uni006B0926

	- uni006B0928

	- uni006B092A

	- uni006B092B

	- uni006B092E

	- uni006B092F

	- uni006B0930

	- uni006B0932

	- uni006B0935

	- uni006B0936

	- uni006B0937

	- uni006B0937094D

	- uni006B0938

	- uni006C00640930

	- uni006C0068092F

	- uni006C006B092F

	- uni006C006C092F

	- uni006C00760921

	- uni006C0915

	- uni006C0916

	- uni006C0917

	- uni006C091C

	- uni006C091F

	- uni006C0920

	- uni006C0921

	- uni006C0922

	- uni006C0924

	- uni006C0925

	- uni006C0926

	- uni006C092A

	- uni006C092B

	- uni006C092C

	- uni006C092D

	- uni006C092E

	- uni006C092F

	- uni006C0930

	- uni006C0932

	- uni006C0935

	- uni006C0938

	- uni006C0939

	- uni006C095B

	- uni006D0062092F

	- uni006D00620930

	- uni006D00700930

	- uni006D0924

	- uni006D0926

	- uni006D0928

	- uni006D092A

	- uni006D092C

	- uni006D092D

	- uni006D092E

	- uni006D092F

	- uni006D0930

	- uni006D0932

	- uni006D0935

	- uni006D0936

	- uni006D0938

	- uni006D0939

	- uni006E00640930

	- uni006E00640935

	- uni006E0068092F

	- uni006E006B0938

	- uni006E006D092F

	- uni006E006E092F

	- uni006E00700930

	- uni006E0073091F

	- uni006E0074092F

	- uni006E00740930

	- uni006E00740938

	- uni006E0915

	- uni006E091A

	- uni006E091F

	- uni006E0921

	- uni006E0924

	- uni006E0925

	- uni006E0926

	- uni006E0927

	- uni006E0928

	- uni006E0928094D

	- uni006E092A

	- uni006E092B

	- uni006E092D

	- uni006E092E

	- uni006E092F

	- uni006E0930

	- uni006E0935

	- uni006E0938

	- uni006E0939

	- uni00700074092F

	- uni0070091F

	- uni00700924

	- uni00700928

	- uni0070092A

	- uni0070092B

	- uni0070092E

	- uni0070092F

	- uni00700930

	- uni00700932

	- uni00700935

	- uni00700938

	- uni00710924

	- uni0071092B

	- uni0071092C

	- uni0071092E

	- uni00710930

	- uni00710958

	- uni0071095E

	- uni0073006B0930

	- uni0073006B0935

	- uni0073006D092F

	- uni007300700930

	- uni00730074092F

	- uni007300740930

	- uni007300740935

	- uni00730915

	- uni00730916

	- uni0073091C

	- uni0073091F

	- uni00730924

	- uni00730925

	- uni00730926

	- uni00730928

	- uni0073092A

	- uni0073092B

	- uni0073092C

	- uni0073092E

	- uni0073092F

	- uni00730930

	- uni00730932

	- uni00730935

	- uni00730938

	- uni0074006B092F

	- uni0074006B0930

	- uni0074006B0935

	- uni0074006B0937

	- uni0074006D092F

	- uni0074006E092F

	- uni007400700930

	- uni007400700932

	- uni007400730928

	- uni00740073092F

	- uni007400730935

	- uni00740074092F

	- uni007400740935

	- uni00740915

	- uni00740916

	- uni00740924

	- uni00740924094D

	- uni00740925

	- uni00740928

	- uni0074092A

	- uni0074092B

	- uni0074092E

	- uni0074092F

	- uni00740930

	- uni00740932

	- uni00740935

	- uni00740938

	- uni00760928

	- uni0076092F

	- uni00760930

	- uni00760932

	- uni00760935

	- uni00760939

	- uni00790928

	- uni0079092F

	- uni00790930

	- uni007A092F

	- uni007A0930

	- uni007A095B

	- uni03000304

	- uni03000304.case

	- uni03000358

	- uni03010304

	- uni03010304.case

	- uni03010358

	- uni0302.case

	- uni03020358

	- uni03030304.case

	- uni03030308.case

	- uni03040300

	- uni03040300.case

	- uni03040301

	- uni03040301.case

	- uni03040358

	- uni0306.case

	- uni03060358

	- uni0308.case

	- uni03080300.case

	- uni03080301.case

	- uni03080304.case

	- uni0308030C.case

	- uni030B.case

	- uni030C.alt

	- uni030C.case

	- uni030D0358

	- uni0312.case

	- uni031B.case

	- uni0324.case

	- uni0325.case

	- uni0326.case

	- uni0327.case

	- uni032E.case

	- uni0330.case

	- va_radeva

	- ya_radeva

	- yy_radeva

	- zero.dnom

	- zero.numr 

	- And zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni018E	Contours detected: 0	Expected: 1

	- Glyph name: uni0197	Contours detected: 0	Expected: 1

	- Glyph name: uni019D	Contours detected: 0	Expected: 1

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01F4	Contours detected: 1	Expected: 2

	- Glyph name: uni01F5	Contours detected: 4	Expected: 3

	- Glyph name: Aringacute	Contours detected: 2	Expected: 3, 4 or 5

	- Glyph name: uni0202	Contours detected: 2	Expected: 3

	- Glyph name: uni0206	Contours detected: 1	Expected: 2

	- Glyph name: uni020A	Contours detected: 1	Expected: 2

	- Glyph name: uni020E	Contours detected: 2	Expected: 3

	- Glyph name: uni0212	Contours detected: 2	Expected: 3

	- Glyph name: uni0216	Contours detected: 1	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0230	Contours detected: 3	Expected: 4

	- Glyph name: uni0232	Contours detected: 1	Expected: 2

	- Glyph name: uni0244	Contours detected: 0	Expected: 2

	- Glyph name: uni0245	Contours detected: 0	Expected: 1

	- Glyph name: uni0249	Contours detected: 0	Expected: 2

	- Glyph name: uni024C	Contours detected: 0	Expected: 2

	- Glyph name: uni024D	Contours detected: 0	Expected: 1

	- Glyph name: uni024F	Contours detected: 0	Expected: 2

	- Glyph name: uni0272	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: uni02CC	Contours detected: 0	Expected: 1

	- Glyph name: uni0313	Contours detected: 0	Expected: 1

	- Glyph name: uni031B	Contours detected: 0	Expected: 1

	- Glyph name: uni0324	Contours detected: 0	Expected: 2

	- Glyph name: uni0325	Contours detected: 0	Expected: 2

	- Glyph name: uni0329	Contours detected: 0	Expected: 1

	- Glyph name: uni0331	Contours detected: 0	Expected: 1

	- Glyph name: uni0334	Contours detected: 0	Expected: 1

	- Glyph name: uni0335	Contours detected: 0	Expected: 1

	- Glyph name: uni0336	Contours detected: 0	Expected: 1

	- Glyph name: uni0337	Contours detected: 0	Expected: 1

	- Glyph name: uni0338	Contours detected: 0	Expected: 1

	- Glyph name: uni0904	Contours detected: 4	Expected: 1

	- Glyph name: uni0905	Contours detected: 2	Expected: 1

	- Glyph name: uni0906	Contours detected: 2	Expected: 1

	- Glyph name: uni0907	Contours detected: 2	Expected: 1

	- Glyph name: uni0908	Contours detected: 2	Expected: 1

	- Glyph name: uni090D	Contours detected: 3	Expected: 2

	- Glyph name: uni090E	Contours detected: 3	Expected: 1

	- Glyph name: uni0910	Contours detected: 2	Expected: 1

	- Glyph name: uni0911	Contours detected: 4	Expected: 2

	- Glyph name: uni0912	Contours detected: 4	Expected: 1

	- Glyph name: uni0913	Contours detected: 3	Expected: 1

	- Glyph name: uni0914	Contours detected: 3	Expected: 1

	- Glyph name: uni091B	Contours detected: 3	Expected: 2

	- Glyph name: uni091D	Contours detected: 3	Expected: 2

	- Glyph name: uni0925	Contours detected: 2	Expected: 1

	- Glyph name: uni0928	Contours detected: 2	Expected: 1

	- Glyph name: uni0929	Contours detected: 3	Expected: 2

	- Glyph name: uni092D	Contours detected: 3	Expected: 1

	- Glyph name: uni092E	Contours detected: 3	Expected: 2

	- Glyph name: uni0936	Contours detected: 3	Expected: 2

	- Glyph name: uni0942	Contours detected: 2	Expected: 1

	- Glyph name: uni0945	Contours detected: 2	Expected: 1

	- Glyph name: uni0946	Contours detected: 2	Expected: 1

	- Glyph name: uni0949	Contours detected: 3	Expected: 2

	- Glyph name: uni094A	Contours detected: 3	Expected: 1

	- Glyph name: uni094B	Contours detected: 2	Expected: 1

	- Glyph name: uni094C	Contours detected: 2	Expected: 1

	- Glyph name: uni094F	Contours detected: 2	Expected: 1

	- Glyph name: uni0950	Contours detected: 4	Expected: 3

	- Glyph name: uni0967	Contours detected: 7	Expected: 1

	- Glyph name: uni0969	Contours detected: 3	Expected: 1

	- Glyph name: uni0970	Contours detected: 6	Expected: 2

	- Glyph name: uni0972	Contours detected: 4	Expected: 2

	- Glyph name: uni0973	Contours detected: 2	Expected: 1

	- Glyph name: uni0974	Contours detected: 2	Expected: 1

	- Glyph name: uni0975	Contours detected: 3	Expected: 1

	- Glyph name: uni0976	Contours detected: 3	Expected: 2

	- Glyph name: uni0977	Contours detected: 4	Expected: 3

	- Glyph name: uni097B	Contours detected: 2	Expected: 1

	- Glyph name: uni097C	Contours detected: 2	Expected: 1

	- Glyph name: uni097F	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0E	Contours detected: 2	Expected: 3

	- Glyph name: uni1E0F	Contours detected: 2	Expected: 3

	- Glyph name: uni1E24	Contours detected: 1	Expected: 2

	- Glyph name: uni1E36	Contours detected: 1	Expected: 2

	- Glyph name: uni1E3E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E46	Contours detected: 1	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 1	Expected: 2

	- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB3	Contours detected: 3	Expected: 4

	- Glyph name: uni2076	Contours detected: 1	Expected: 2

	- Glyph name: uni2079	Contours detected: 1	Expected: 2

	- Glyph name: uni2086	Contours detected: 1	Expected: 2

	- Glyph name: uni2089	Contours detected: 1	Expected: 2

	- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

	- Glyph name: uni20B9	Contours detected: 3	Expected: 1

	- Glyph name: arrowleft	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowright	Contours detected: 2	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uniA78B	Contours detected: 0	Expected: 1

	- Glyph name: uniA78C	Contours detected: 0	Expected: 1

	- Glyph name: Aringacute	Contours detected: 2	Expected: 3, 4 or 5

	- Glyph name: arrowboth	Contours detected: 3	Expected: 1

	- Glyph name: arrowdown	Contours detected: 2	Expected: 1

	- Glyph name: arrowup	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 3	Expected: 1

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni018E	Contours detected: 0	Expected: 1

	- Glyph name: uni0197	Contours detected: 0	Expected: 1

	- Glyph name: uni019D	Contours detected: 0	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0230	Contours detected: 3	Expected: 4

	- Glyph name: uni0232	Contours detected: 1	Expected: 2

	- Glyph name: uni0244	Contours detected: 0	Expected: 2

	- Glyph name: uni0245	Contours detected: 0	Expected: 1

	- Glyph name: uni0249	Contours detected: 0	Expected: 2

	- Glyph name: uni024C	Contours detected: 0	Expected: 2

	- Glyph name: uni024D	Contours detected: 0	Expected: 1

	- Glyph name: uni024F	Contours detected: 0	Expected: 2

	- Glyph name: uni0272	Contours detected: 0	Expected: 1

	- Glyph name: uni02BB	Contours detected: 0	Expected: 1

	- Glyph name: uni02BC	Contours detected: 0	Expected: 1

	- Glyph name: uni02BE	Contours detected: 0	Expected: 1

	- Glyph name: uni02BF	Contours detected: 0	Expected: 1

	- Glyph name: uni02C8	Contours detected: 0	Expected: 1

	- Glyph name: uni02CA	Contours detected: 0	Expected: 1

	- Glyph name: uni02CB	Contours detected: 0	Expected: 1

	- Glyph name: uni02CC	Contours detected: 0	Expected: 1

	- Glyph name: uni0313	Contours detected: 0	Expected: 1

	- Glyph name: uni031B	Contours detected: 0	Expected: 1

	- Glyph name: uni0324	Contours detected: 0	Expected: 2

	- Glyph name: uni0325	Contours detected: 0	Expected: 2

	- Glyph name: uni0329	Contours detected: 0	Expected: 1

	- Glyph name: uni0331	Contours detected: 0	Expected: 1

	- Glyph name: uni0335	Contours detected: 0	Expected: 1

	- Glyph name: uni0336	Contours detected: 0	Expected: 1

	- Glyph name: uni0337	Contours detected: 0	Expected: 1

	- Glyph name: uni0338	Contours detected: 0	Expected: 1

	- Glyph name: uni0904	Contours detected: 4	Expected: 1

	- Glyph name: uni0905	Contours detected: 2	Expected: 1

	- Glyph name: uni0906	Contours detected: 2	Expected: 1

	- Glyph name: uni0907	Contours detected: 2	Expected: 1

	- Glyph name: uni0908	Contours detected: 2	Expected: 1

	- Glyph name: uni090D	Contours detected: 3	Expected: 2

	- Glyph name: uni090E	Contours detected: 3	Expected: 1

	- Glyph name: uni0910	Contours detected: 2	Expected: 1

	- Glyph name: uni0911	Contours detected: 4	Expected: 2

	- Glyph name: uni0912	Contours detected: 4	Expected: 1

	- Glyph name: uni0913	Contours detected: 3	Expected: 1

	- Glyph name: uni0914	Contours detected: 3	Expected: 1

	- Glyph name: uni091B	Contours detected: 3	Expected: 2

	- Glyph name: uni091D	Contours detected: 3	Expected: 2

	- Glyph name: uni0925	Contours detected: 2	Expected: 1

	- Glyph name: uni0928	Contours detected: 2	Expected: 1

	- Glyph name: uni0929	Contours detected: 3	Expected: 2

	- Glyph name: uni092D	Contours detected: 3	Expected: 1

	- Glyph name: uni092E	Contours detected: 3	Expected: 2

	- Glyph name: uni0936	Contours detected: 3	Expected: 2

	- Glyph name: uni0942	Contours detected: 2	Expected: 1

	- Glyph name: uni0945	Contours detected: 2	Expected: 1

	- Glyph name: uni0946	Contours detected: 2	Expected: 1

	- Glyph name: uni0949	Contours detected: 3	Expected: 2

	- Glyph name: uni094A	Contours detected: 3	Expected: 1

	- Glyph name: uni094B	Contours detected: 2	Expected: 1

	- Glyph name: uni094C	Contours detected: 2	Expected: 1

	- Glyph name: uni094F	Contours detected: 2	Expected: 1

	- Glyph name: uni0950	Contours detected: 4	Expected: 3

	- Glyph name: uni0967	Contours detected: 7	Expected: 1

	- Glyph name: uni0969	Contours detected: 3	Expected: 1

	- Glyph name: uni0970	Contours detected: 6	Expected: 2

	- Glyph name: uni0972	Contours detected: 4	Expected: 2

	- Glyph name: uni0973	Contours detected: 2	Expected: 1

	- Glyph name: uni0974	Contours detected: 2	Expected: 1

	- Glyph name: uni0975	Contours detected: 3	Expected: 1

	- Glyph name: uni0976	Contours detected: 3	Expected: 2

	- Glyph name: uni0977	Contours detected: 4	Expected: 3

	- Glyph name: uni097B	Contours detected: 2	Expected: 1

	- Glyph name: uni097C	Contours detected: 2	Expected: 1

	- Glyph name: uni097F	Contours detected: 4	Expected: 3

	- Glyph name: uni1E0E	Contours detected: 2	Expected: 3

	- Glyph name: uni1E0F	Contours detected: 2	Expected: 3

	- Glyph name: uni1E24	Contours detected: 1	Expected: 2

	- Glyph name: uni1E36	Contours detected: 1	Expected: 2

	- Glyph name: uni1E3E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E46	Contours detected: 1	Expected: 2

	- Glyph name: uni1E6E	Contours detected: 1	Expected: 2

	- Glyph name: uni1E6F	Contours detected: 1	Expected: 2

	- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB3	Contours detected: 3	Expected: 4

	- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

	- Glyph name: uni20B9	Contours detected: 3	Expected: 1

	- Glyph name: uni2196	Contours detected: 2	Expected: 1

	- Glyph name: uni2197	Contours detected: 2	Expected: 1

	- Glyph name: uni2198	Contours detected: 2	Expected: 1

	- Glyph name: uni2199	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uniA78B	Contours detected: 0	Expected: 1 

	- And Glyph name: uniA78C	Contours detected: 0	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* AE (U+00C6): L<<380.0,642.0>--<344.0,563.0>> -> L<<344.0,563.0>--<215.0,254.0>>

	* AEacute (U+01FC): L<<380.0,642.0>--<344.0,563.0>> -> L<<344.0,563.0>--<215.0,254.0>>

	* M (U+004D): L<<413.0,0.0>--<263.0,407.0>> -> L<<263.0,407.0>--<219.0,561.0>>

	* Z (U+005A): L<<504.0,589.0>--<189.0,130.0>> -> L<<189.0,130.0>--<122.0,46.0>>

	* Z (U+005A): L<<64.0,110.0>--<378.0,564.0>> -> L<<378.0,564.0>--<420.0,614.0>>

	* Zacute (U+0179): L<<504.0,589.0>--<189.0,130.0>> -> L<<189.0,130.0>--<122.0,46.0>>

	* Zacute (U+0179): L<<64.0,110.0>--<378.0,564.0>> -> L<<378.0,564.0>--<420.0,614.0>>

	* Zcaron (U+017D): L<<504.0,589.0>--<189.0,130.0>> -> L<<189.0,130.0>--<122.0,46.0>>

	* Zcaron (U+017D): L<<64.0,110.0>--<378.0,564.0>> -> L<<378.0,564.0>--<420.0,614.0>>

	* Zdotaccent (U+017B): L<<504.0,589.0>--<189.0,130.0>> -> L<<189.0,130.0>--<122.0,46.0>>

	* Zdotaccent (U+017B): L<<64.0,110.0>--<378.0,564.0>> -> L<<378.0,564.0>--<420.0,614.0>>

	* asterisk (U+002A): L<<173.0,359.0>--<254.0,470.0>> -> L<<254.0,470.0>--<313.0,539.0>>

	* b (U+0062): L<<144.0,714.0>--<144.0,561.0>> -> L<<144.0,561.0>--<136.0,417.0>>

	* d (U+0064): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* dcaron (U+010F): L<<359.0,466.0>--<354.0,558.0>> -> L<<354.0,558.0>--<354.0,652.0>>

	* kgreenlandic (U+0138): L<<428.0,417.0>--<409.0,400.0>> -> L<<409.0,400.0>--<296.0,287.0>>

	* sterling (U+00A3): L<<236.0,336.0>--<238.0,233.0>> -> L<<238.0,233.0>--<238.0,212.0>>

	* thorn (U+00FE): L<<154.0,704.0>--<154.0,561.0>> -> L<<154.0,561.0>--<144.0,416.0>>

	* uni01C4 (U+01C4): L<<1152.0,589.0>--<837.0,130.0>> -> L<<837.0,130.0>--<770.0,46.0>>

	* uni01C4 (U+01C4): L<<712.0,110.0>--<1026.0,564.0>> -> L<<1026.0,564.0>--<1068.0,614.0>>

	* uni01C6 (U+01C6): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* uni0233 (U+0233): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* uni0233 (U+0233): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* uni093D (U+093D): L<<439.0,664.0>--<443.0,659.0>> -> L<<443.0,659.0>--<454.0,643.0>>

	* uni0950 (U+0950): L<<102.0,104.0>--<102.0,104.0>> -> L<<102.0,104.0>--<103.0,104.0>>

	* uni0970 (U+0970): L<<334.0,442.0>--<313.0,444.0>> -> L<<313.0,444.0>--<308.0,444.0>>

	* uni1E03 (U+1E03): L<<144.0,714.0>--<144.0,561.0>> -> L<<144.0,561.0>--<136.0,417.0>>

	* uni1E05 (U+1E05): L<<144.0,714.0>--<144.0,561.0>> -> L<<144.0,561.0>--<136.0,417.0>>

	* uni1E0B (U+1E0B): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* uni1E0D (U+1E0D): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* uni1E0F (U+1E0F): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* uni1E13 (U+1E13): L<<361.0,466.0>--<356.0,558.0>> -> L<<356.0,558.0>--<356.0,652.0>>

	* uni1E3E (U+1E3E): L<<413.0,0.0>--<263.0,407.0>> -> L<<263.0,407.0>--<219.0,561.0>>

	* uni1E40 (U+1E40): L<<413.0,0.0>--<263.0,407.0>> -> L<<263.0,407.0>--<219.0,561.0>>

	* uni1E92 (U+1E92): L<<504.0,589.0>--<189.0,130.0>> -> L<<189.0,130.0>--<122.0,46.0>>

	* uni1E92 (U+1E92): L<<64.0,110.0>--<378.0,564.0>> -> L<<378.0,564.0>--<420.0,614.0>>

	* uni1EF5 (U+1EF5): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* uni1EF5 (U+1EF5): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* uni1EF7 (U+1EF7): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* uni1EF7 (U+1EF7): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* uni1EF9 (U+1EF9): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* uni1EF9 (U+1EF9): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* w (U+0077): L<<205.0,-10.0>--<42.0,395.0>> -> L<<42.0,395.0>--<34.0,412.0>>

	* w (U+0077): L<<320.0,333.0>--<297.0,395.0>> -> L<<297.0,395.0>--<289.0,412.0>>

	* wacute (U+1E83): L<<205.0,-10.0>--<42.0,395.0>> -> L<<42.0,395.0>--<34.0,412.0>>

	* wacute (U+1E83): L<<320.0,333.0>--<297.0,395.0>> -> L<<297.0,395.0>--<289.0,412.0>>

	* wcircumflex (U+0175): L<<205.0,-10.0>--<42.0,395.0>> -> L<<42.0,395.0>--<34.0,412.0>>

	* wcircumflex (U+0175): L<<320.0,333.0>--<297.0,395.0>> -> L<<297.0,395.0>--<289.0,412.0>>

	* wdieresis (U+1E85): L<<205.0,-10.0>--<42.0,395.0>> -> L<<42.0,395.0>--<34.0,412.0>>

	* wdieresis (U+1E85): L<<320.0,333.0>--<297.0,395.0>> -> L<<297.0,395.0>--<289.0,412.0>>

	* wgrave (U+1E81): L<<205.0,-10.0>--<42.0,395.0>> -> L<<42.0,395.0>--<34.0,412.0>>

	* wgrave (U+1E81): L<<320.0,333.0>--<297.0,395.0>> -> L<<297.0,395.0>--<289.0,412.0>>

	* y (U+0079): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* y (U+0079): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* yacute (U+00FD): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* yacute (U+00FD): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* ycircumflex (U+0177): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* ycircumflex (U+0177): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* ydieresis (U+00FF): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>>

	* ydieresis (U+00FF): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>>

	* ygrave (U+1EF3): L<<125.0,416.0>--<214.0,181.0>> -> L<<214.0,181.0>--<257.0,48.0>> 

	* And ygrave (U+1EF3): L<<257.0,48.0>--<289.0,181.0>> -> L<<289.0,181.0>--<367.0,416.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* OE (U+0152): B<<523.5,561.0>-<549.0,510.0>-<560.0,446.0>>/L<<560.0,446.0>--<560.0,603.0>> = 9.752424941653764

	* OE (U+0152): L<<560.0,55.0>--<560.0,253.0>>/B<<560.0,253.0>-<547.0,180.0>-<514.0,119.0>> = 10.09750438407527

	* onehalf (U+00BD): B<<651.0,313.5>-<652.0,311.0>-<653.0,310.0>>/L<<653.0,310.0>--<650.0,312.0>> = 11.309932474020195

	* onehalf (U+00BD): L<<653.0,310.0>--<650.0,312.0>>/B<<650.0,312.0>-<654.0,308.0>-<654.5,306.5>> = 11.309932474020195

	* trademark (U+2122): L<<958.0,594.0>--<859.0,282.0>>/L<<859.0,282.0>--<860.0,284.0>> = 8.96041784041399

	* uni0904 (U+0904): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0905 (U+0905): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0906 (U+0906): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0911 (U+0911): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0912 (U+0912): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0913 (U+0913): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0914 (U+0914): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni091E (U+091E): B<<19.5,179.5>-<28.0,184.0>-<42.0,171.0>>/B<<42.0,171.0>-<40.0,173.0>-<39.0,174.0>> = 2.1210963966611036

	* uni093A (U+093A): B<<-39.5,673.5>-<-48.0,690.0>-<-49.0,697.0>>/B<<-49.0,697.0>-<-49.0,694.0>-<-49.5,714.0>> = 8.13010235415596

	* uni0950 (U+0950): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0951 (U+0951): B<<-30.5,763.5>-<-39.0,780.0>-<-40.0,787.0>>/B<<-40.0,787.0>-<-40.0,784.0>-<-40.5,804.0>> = 8.13010235415596

	* uni0972 (U+0972): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0973 (U+0973): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0974 (U+0974): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0975 (U+0975): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0976 (U+0976): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni0977 (U+0977): L<<112.0,96.0>--<107.0,100.0>>/B<<107.0,100.0>-<109.0,98.0>-<110.5,96.5>> = 6.340191745909908

	* uni097A (U+097A): B<<304.5,457.5>-<246.0,521.0>-<189.0,585.0>>/B<<189.0,585.0>-<206.0,557.0>-<216.0,525.0>> = 10.425326791011116

	* uni2120 (U+2120): L<<340.0,596.0>--<342.0,594.0>>/B<<342.0,594.0>-<331.0,610.0>-<309.0,621.5>> = 10.491477012331599 

	* And uni2120 (U+2120): L<<878.0,598.0>--<780.0,282.0>>/L<<780.0,282.0>--<781.0,284.0>> = 9.334998463138216 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<380.0,657.0>--<657.0,658.0>>

	* AEacute (U+01FC): L<<380.0,657.0>--<657.0,658.0>>

	* Eng (U+014A): L<<604.0,584.0>--<603.0,16.0>>

	* b (U+0062): L<<59.0,42.0>--<60.0,659.0>>

	* brokenbar (U+00A6): L<<154.0,209.0>--<152.0,-243.0>>

	* brokenbar (U+00A6): L<<154.0,821.0>--<152.0,369.0>>

	* brokenbar (U+00A6): L<<70.0,-278.0>--<72.0,175.0>>

	* brokenbar (U+00A6): L<<70.0,334.0>--<72.0,787.0>>

	* d (U+0064): L<<357.0,77.0>--<356.0,381.0>>

	* dcaron (U+010F): L<<355.0,77.0>--<354.0,381.0>>

	* dcroat (U+0111): L<<355.0,77.0>--<354.0,381.0>>

	* dong (U+20AB): L<<355.0,186.0>--<353.0,456.0>>

	* eng (U+014B): L<<392.0,6.0>--<390.0,291.0>>

	* eng (U+014B): L<<478.0,329.0>--<479.0,16.0>>

	* m (U+006D): L<<183.0,370.0>--<182.0,74.0>>

	* m (U+006D): L<<674.0,51.0>--<673.0,289.0>>

	* thorn (U+00FE): L<<151.0,380.0>--<152.0,81.0>>

	* u (U+0075): L<<63.0,132.0>--<61.0,405.0>>

	* uacute (U+00FA): L<<63.0,132.0>--<61.0,405.0>>

	* ubreve (U+016D): L<<63.0,132.0>--<61.0,405.0>>

	* ucircumflex (U+00FB): L<<63.0,132.0>--<61.0,405.0>>

	* udieresis (U+00FC): L<<63.0,132.0>--<61.0,405.0>>

	* ugrave (U+00F9): L<<63.0,132.0>--<61.0,405.0>>

	* uhorn (U+01B0): L<<63.0,132.0>--<61.0,405.0>>

	* uhungarumlaut (U+0171): L<<63.0,132.0>--<61.0,405.0>>

	* umacron (U+016B): L<<63.0,132.0>--<61.0,405.0>>

	* uni01C6 (U+01C6): L<<357.0,77.0>--<356.0,381.0>>

	* uni01D4 (U+01D4): L<<63.0,132.0>--<61.0,405.0>>

	* uni01D6 (U+01D6): L<<63.0,132.0>--<61.0,405.0>>

	* uni01D8 (U+01D8): L<<63.0,132.0>--<61.0,405.0>>

	* uni01DA (U+01DA): L<<63.0,132.0>--<61.0,405.0>>

	* uni01DC (U+01DC): L<<63.0,132.0>--<61.0,405.0>>

	* uni0215 (U+0215): L<<63.0,132.0>--<61.0,405.0>>

	* uni0217 (U+0217): L<<63.0,132.0>--<61.0,405.0>>

	* uni091B (U+091B): L<<591.0,609.0>--<233.0,608.0>>

	* uni092A (U+092A): L<<454.0,364.0>--<455.0,609.0>>

	* uni0937 (U+0937): L<<465.0,364.0>--<466.0,609.0>>

	* uni1E03 (U+1E03): L<<59.0,42.0>--<60.0,659.0>>

	* uni1E05 (U+1E05): L<<59.0,42.0>--<60.0,659.0>>

	* uni1E0B (U+1E0B): L<<357.0,77.0>--<356.0,381.0>>

	* uni1E0D (U+1E0D): L<<357.0,77.0>--<356.0,381.0>>

	* uni1E0F (U+1E0F): L<<357.0,77.0>--<356.0,381.0>>

	* uni1E13 (U+1E13): L<<357.0,77.0>--<356.0,381.0>>

	* uni1E3F (U+1E3F): L<<183.0,370.0>--<182.0,74.0>>

	* uni1E3F (U+1E3F): L<<674.0,51.0>--<673.0,289.0>>

	* uni1E41 (U+1E41): L<<183.0,370.0>--<182.0,74.0>>

	* uni1E41 (U+1E41): L<<674.0,51.0>--<673.0,289.0>>

	* uni1EE5 (U+1EE5): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EE7 (U+1EE7): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EE9 (U+1EE9): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EEB (U+1EEB): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EED (U+1EED): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EEF (U+1EEF): L<<63.0,132.0>--<61.0,405.0>>

	* uni1EF1 (U+1EF1): L<<63.0,132.0>--<61.0,405.0>>

	* uogonek (U+0173): L<<63.0,132.0>--<61.0,405.0>>

	* uring (U+016F): L<<63.0,132.0>--<61.0,405.0>> 

	* And utilde (U+0169): L<<63.0,132.0>--<61.0,405.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 11 | 108 | 7 | 92 | 0 |
| 0% | 4% | 5% | 48% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
