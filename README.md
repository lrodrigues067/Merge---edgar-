#file name: Merging the Datasets
#objective: Unite all the datasets by following the alphabet
#author: Leticia Rodrigues
#created on: February - March (2021)
#last accessed on:

#install.packages(dplyr)
library(dplyr)

#Merging the datasets of the companys that starts with the letter A - ok

A = rbind(threeM, ap) %>% 
  rbind(electrolux) %>%
  rbind(abb) %>% 
  rbind(abbey) %>% 
  rbind(abbott) %>% 
  rbind(abbvie) %>% 
  rbind(abn) %>% 
  rbind(accenture) %>% 
  rbind(acciona) %>% 
  rbind(acer) %>% 
  rbind(achmea) %>% 
  rbind(acs) %>% 
  rbind(adecco) %>% 
  rbind(adeccosa) %>% 
  rbind(adidas) %>%  
  rbind(advance) %>% 
  rbind(aegon) %>%  
  rbind(aeon) %>%  
  rbind(aescorp) %>% 
  rbind(aetna) %>% 
  rbind(aflac) %>% 
  rbind(ageas) %>% 
  rbind(agri_bank_chi) %>% 
  rbind(aia) %>% 
  rbind(aig) %>% 
  rbind(airfrance) %>% 
  rbind(airbus) %>% 
  rbind(aisin) %>% 
  rbind(akzo) %>% 
  rbind(albertson) %>% 
  rbind(alcan) %>% 
  rbind(alcan_alumin) %>% 
  rbind(alcatel) %>%
  rbind(alco) %>%
  rbind(alcoa) %>%
  rbind(alcoainc) %>%
  rbind(alfresa) %>%
  rbind(alibaba) %>%
  rbind(alimentation) %>%
  rbind(allnippon) %>%
  rbind(allegheny) %>%
  rbind(alliance) %>%
  rbind(alliance_uni) %>%
  rbind(allianz) %>%
  rbind(alliedsignal) %>%
  rbind(allstate) %>%
  rbind(alphabet) %>% 
  rbind(alstom) %>% 
  rbind(altadis) %>%
  rbind(altice) %>%
  rbind(altria) %>%
  rbind(aluminum_company) %>%
  rbind(aluminum_china) %>%
  rbind(amazon) %>%
  rbind(amer) %>%
  rbind(amerada) %>%
  rbind(america_movil) %>%
  rbind(america_telecom) %>%
  rbind(american_airlines) %>%
  rbind(american_electric) %>%
  rbind(american_express) %>%
  rbind(american_general) %>%
  rbind(american_home) %>%
  rbind(american_intl) %>%
  rbind(american_stores) %>%
  rbind(amerisource_health) %>%
  rbind(amerisourcebergen) %>%
  rbind(ameritech) %>%
  rbind(amgen) %>%
  rbind(amoco) %>%
  rbind(amp) %>%
  rbind(andeavor) %>%
  rbind(anglo) %>%
  rbind(anheuser) %>%
  rbind(anthem) %>%
  rbind(aol) %>%
  rbind(apple) %>%
  rbind(aquila) %>%
  rbind(arcelor) %>%
  rbind(archer) %>%
  rbind(arconic) %>%
  rbind(areva) %>%
  rbind(argyll) %>%
  rbind(arrow) %>%
  rbind(asahi_bank) %>%
  rbind(asahi_chemical) %>%
  rbind(asahi_glass) %>%
  rbind(asahi_kasei) %>%
  rbind(asahi_mutual) %>%
  rbind(asda) %>%
  rbind(ashland) %>%
  rbind(assicurazioni) %>%
  rbind(associates) %>%
  rbind(assurances) %>%
  rbind(astrazeneca) %>%
  rbind(asustek) %>%
  rbind(att) %>%
  rbind(atlantic) %>%
  rbind(aus_nz_bnkg) %>%
  rbind(autonation) %>%
  rbind(aventis) %>%
  rbind(aviva) %>%
  rbind(avnet) %>%
  rbind(axa) 

write.csv(A, "A")

#Merging the datasets of companys that have a 10-k report starting with the letter B  
B = rbind(bat, bae) %>%
   rbind(baker) %>%
   rbind(banc_one) %>%
   rbind(banca_commerciale) %>%
   rbind(banca_intensa) %>%
   rbind(banca_monte) %>%
   rbind(bilbao) %>%
   rbind(bradesco) %>%
   rbind(banco_central) %>%
   rbind(banco_dobrasil) %>%
   rbind(santander) %>%
   rbind(bank_of_america) %>%
   rbind(bank_of_china) %>%
   rbind(bank_of_communications) %>%
   rbind(bank_of_ireland) %>%
   rbind(bank_of_montreal) %>%
   rbind(bank_of_ns) %>%
   rbind(bank_of_sctld) %>%
   rbind(bank_one) %>%
   rbind(bankamerica) %>%
   rbind(bankers_trust) %>%
   rbind(bankgesellschaft) %>%
   rbind(banque) %>%
   rbind(barclays) %>%
   rbind(basf) %>%
   rbind(baxter) %>%
   rbind(bayer) %>%
   rbind(bayerische_wechsel) %>%
   rbind(bayerische_hypo) %>%
   rbind(bayerische_land) %>%
   rbind(bayerische_mot) %>%
   rbind(bayerische_vere) %>%
   rbind(bce) %>%
   rbind(bear_stearns) %>%
   rbind(bell_atlantic) %>%
   rbind(bergen) %>%
   rbind(berkshire) %>%
   rbind(bertelsmann) %>%
   rbind(best_buy) %>%
   rbind(bestfoods) %>%
   rbind(bg_group) %>%
   rbind(bharat) %>%
   rbind(bhp_billiton) %>%
   rbind(bmw) %>%
   rbind(bnp) %>%
   rbind(boehringer) %>%
   rbind(bell_atlantic) %>%
   rbind(boeing) %>%
   rbind(bombardier) %>%
   rbind(bosch) %>%
   rbind(bouygues) %>%
   rbind(bp) %>%
   rbind(brazilian_dist) %>%
   rbind(bridgestone) %>%
   rbind(bristol) %>%
   rbind(british_aerospace) %>%
   rbind(british_airways) %>%
   rbind(british_tobacco) %>%
   rbind(british_gas) %>%
   rbind(british_steel) %>%
   rbind(british_tele) %>%
   rbind(brookfield) %>%
   rbind(bt) %>%
   rbind(btr) %>%
   rbind(bunge) %>%
   rbind(burlington)

write.csv(B,"B")

#Merging the datasets of companys that have a 10-k report starting with the latter C - ok
C = rbind(cable, caltex) %>% 
  rbind(canadian_imp) %>% 
  rbind(abn) %>% 
  rbind(canadian_pacific) %>% 
  rbind(canon) %>% 
  rbind(capital_one) %>% 
  rbind(cardinal) %>% 
  rbind(caremark) %>% 
  rbind(carrefour) %>% 
  rbind(carso) %>% 
  rbind(caterpillar) %>%  
  rbind(cathay_financial) %>% 
  rbind(cbs) %>%  
  rbind(ceconomy) %>%  
  rbind(cemex) %>% 
  rbind(centene) %>% 
  rbind(centex) %>% 
  rbind(central_japan) %>% 
  rbind(centrica) %>% 
  rbind(cgnu) %>% 
  rbind(charter_com) %>% 
  rbind(chase_manhattan) %>% 
  rbind(chemchina) %>% 
  rbind(chem_banking) %>% 
  rbind(chevron) %>% 
  rbind(china_com) %>% 
  rbind(china_construction) %>% 
  rbind(cosco) %>% 
  rbind(datang) %>%
  rbind(china_bank) %>%
  rbind(china_electronics) %>%
  rbind(china_energy_eng) %>%
  rbind(china_energy) %>%
  rbind(china_everbright) %>%
  rbind(china_evergrande) %>%
  rbind(china_huadian) %>%
  rbind(china_huaneng) %>%
  rbind(china_life) %>%
  rbind(china_merchants) %>%
  rbind(china_metallurgical) %>%
  rbind(china_minmetals) %>%
  rbind(china_minsheng) %>%
  rbind(china_mobile) %>% 
  rbind(china_bldg) %>% 
  rbind(china_chem) %>%
  rbind(china_machinery) %>%
  rbind(china_offshore) %>%
  rbind(china_pet) %>%
  rbind(china_pharm) %>%
  rbind(china_nonferrous) %>%
  rbind(china_ocean) %>%
  rbind(china_pacific) %>%
  rbind(china_petroch) %>%
  rbind(china_poly) %>%
  rbind(china_power) %>%
  rbind(china_railway) %>%
  rbind(china_engineering) %>%
  rbind(china_resources) %>%
  rbind(china_taiping) %>%
  rbind(china_tele) %>%
  rbind(china_united) %>%
  rbind(china_united_tel) %>%
  rbind(china_vanke) %>%
  rbind(chinese_petr) %>%
  rbind(dior) %>%
  rbind(chrysler) %>%
  rbind(chs) %>%
  rbind(chubb) %>%
  rbind(chubu) %>%
  rbind(ciba) %>%
  rbind(cie_nationale) %>%
  rbind(cigna) %>%
  rbind(cinergy) %>%
  rbind(circuit) %>%
  rbind(cisco) %>%
  rbind(citic) %>%
  rbind(citicorp) %>%
  rbind(citigroup) %>%
  rbind(cj) %>%
  rbind(ck) %>%
  rbind(cms) %>%
  rbind(cnp) %>%
  rbind(michelin) %>%
  rbind(cocacola) %>%
  rbind(coles) %>%
  rbind(coles_myer) %>%
  rbind(colgate) %>%
  rbind(college) %>%
  rbind(hca) %>%
  rbind(comcast) %>%
  rbind(commercial_union) %>%
  rbind(commerzbank) %>%
  rbind(commonwealth) %>%
  rbind(community_health) %>%
  rbind(saintgobain) %>%
  rbind(suez) %>%
  rbind(compagnie_generale) %>%
  rbind(air_france) %>%
  rbind(compal) %>%
  rbind(compania_espanola) %>%
  rbind(compaq) %>%
  rbind(compass) %>%
  rbind(comp_sciences) %>%
  rbind(conagra) %>%
  rbind(conagra_inc) %>%
  rbind(conoco) %>%
  rbind(constellation) %>%
  rbind(continental) %>%
  rbind(coop) %>%
  rbind(corus) %>%
  rbind(cosmo) %>%
  rbind(costco) %>%
  rbind(country_garden) %>%
  rbind(countrywide) %>%
  rbind(cpc) %>%
  rbind(credit_agricole) %>%
  rbind(credit_lyonnais) %>%
  rbind(credit_industriel) %>%
  rbind(credit_nationale) %>%
  rbind(credit_suisse) %>%
  rbind(credito_it) %>%
  rbind(crh) %>%
  rbind(crrc) %>%
  rbind(cs_holding) %>%
  rbind(csx) %>%
  rbind(cvrd) %>%
  rbind(cvs) 
  
write.csv(C,"C")


#Merging the datasets of companys that have a 10-k report starting with the latter D - ok
D = rbind(dr_horton, dai_nippon) %>% 
  rbind(daido) %>% 
  rbind(daiei) %>% 
  rbind(daiichi_holdings) %>% 
  rbind(daiichi_life) %>% 
  rbind(daimler) %>% 
  rbind(daiwa) %>% 
  rbind(daiwa_house) %>% 
  rbind(dalian) %>% 
  rbind(dana) %>% 
  rbind(danone) %>%  
  rbind(danske) %>% 
  rbind(dayton) %>%  
  rbind(ddi) %>%  
  rbind(deere) %>% 
  rbind(degussa) %>% 
  rbind(delhaize) %>% 
  rbind(dell) %>% 
  rbind(delphi) %>% 
  rbind(delta) %>% 
  rbind(den_norske) %>% 
  rbind(denso) %>% 
  rbind(dentsu) %>% 
  rbind(deutsche_bank) %>% 
  rbind(lufthansa) %>% 
  rbind(deutsche_post) %>% 
  rbind(deutsche_telekom) %>% 
  rbind(dexia) %>% 
  rbind(diageo) %>%
  rbind(digital_corp) %>%
  rbind(directv) %>%
  rbind(dollar) %>%
  rbind(dominion) %>%
  rbind(dongfeng) %>%
  rbind(dow_chemical) %>%
  rbind(dupont) %>%
  rbind(dresdner) %>%
  rbind(duke) %>%
  rbind(dxc) %>%
  rbind(dynegy) %>%
  rbind(dz_bank) 

write.csv(D,"D")

#Merging the datasets of companys that have a 10-k report starting with the latter E - ok
E = rbind(ei_dupont, eads) %>% 
  rbind(east_japan) %>% 
  rbind(eastman) %>% 
  rbind(ecopetrol) %>% 
  rbind(edison) %>% 
  rbind(edp) %>% 
  rbind(eiffage) %>% 
  rbind(elpaso) %>% 
  rbind(electricite_france) %>% 
  rbind(electrolux) %>% 
  rbind(electronic) %>%  
  rbind(elf) %>% 
  rbind(eli) %>%  
  rbind(emc) %>%  
  rbind(emerson) %>% 
  rbind(enbridge) %>% 
  rbind(encana) %>% 
  rbind(endesa) %>% 
  rbind(enel) %>% 
  rbind(energy_transfer) %>% 
  rbind(eni) %>% 
  rbind(enron) %>% 
  rbind(entergy) %>% 
  rbind(enterprise_gp) %>% 
  rbind(enterprise_products) %>% 
  rbind(equinor) %>% 
  rbind(ericsson) %>% 
  rbind(erste_bank) %>% 
  rbind(eurohypo) %>%
  rbind(european_aeronautic) %>%
  rbind(evergrande) %>%
  rbind(evonik) %>%
  rbind(evraz) %>%
  rbind(exelon) %>%
  rbind(exor) %>%
  rbind(express_scripts) %>%
  rbind(exxon) 

write.csv(E,"E")

#Merging the datasets of companys that have a 10-k report starting with the latter F - ok
f = rbind(facebook, fannie_mae) %>% 
  rbind(farmland) %>% 
  rbind(fdx) %>% 
  rbind(fed_home) %>% 
  rbind(fed_department) %>% 
  rbind(fedex) %>% 
  rbind(fiat) %>% 
  rbind(finmecanica) %>% 
  rbind(first_chicago) %>% 
  rbind(first_union) %>% 
  rbind(firstenergy) %>%  
  rbind(fleet_fin) %>% 
  rbind(fleetboston) %>%  
  rbind(fleming) %>%  
  rbind(flex) %>% 
  rbind(fluor) %>% 
  rbind(fomento_const) %>% 
  rbind(fomento_economico) %>% 
  rbind(ford) %>% 
  rbind(fortis) %>% 
  rbind(fortum) %>% 
  rbind(france_telecom) %>% 
  rbind(fred_meyer) %>%
  rbind(freddie_mac) %>% 
  rbind(freeport) %>% 
  rbind(fresenius) %>% 
  rbind(friends) %>% 
  rbind(fubon) %>% 
  rbind(fuji_elect) %>% 
  rbind(fuji_heavy) %>%
  rbind(fuji_photo) %>%
  rbind(fujifilm) %>%
  rbind(fujitsu) %>%
  rbind(fukoku)

write.csv(f,"f")

#Merging the datasets of companys that have a 10-k report starting with the latter G - ok
G = rbind(galp, gan) %>% 
  rbind(gap) %>% 
  rbind(gas_natural) %>% 
  rbind(gaz_france) %>% 
  rbind(gazprom) %>% 
  rbind(gdf_suez) %>% 
  rbind(gec) %>% 
  rbind(general_accident) %>% 
  rbind(general_dynamics) %>% 
  rbind(general_motors) %>% 
  rbind(generale_bank) %>%  
  rbind(georgia_pacific) %>% 
  rbind(gilead) %>%  
  rbind(gilette) %>%  
  rbind(glaxo) %>% 
  rbind(glaxo_smith) %>% 
  rbind(glencore) %>% 
  rbind(goldman_sachs) %>% 
  rbind(goodyear) %>% 
  rbind(google) %>% 
  rbind(grand_metropolitan) %>% 
  rbind(great_atl) %>% 
  rbind(greenland) %>%
  rbind(groupama) %>% 
  rbind(bpce) %>% 
  rbind(casino) %>% 
  rbind(groupe_pinault) %>% 
  rbind(grupo_ferrovial) %>% 
  rbind(grupo_cassa) %>% 
  rbind(mediolanum) %>%
  rbind(gs_holdings) %>%
  rbind(gte) %>%
  rbind(guangzhou) %>%
  rbind(gus) 

write.csv(G,"G")

#Merging the datasets of companys that have a 10-k report starting with the latter H
H = rbind(hm, heinz) %>% 
  rbind(halifax) %>% 
  rbind(halliburton) %>% 
  rbind(hanson) %>% 
  rbind(hanwha) %>% 
  rbind(hartford) %>% 
  rbind(havas) %>% 
  rbind(hbis) %>% 
  rbind(hbos) %>% 
  rbind(hca) %>% 
  rbind(hca_holdings) %>%  
  rbind(health_net) %>% 
  rbind(hebei) %>%  
  rbind(heidelberg_cement) %>%  
  rbind(heineken) %>% 
  rbind(henkel) %>% 
  rbind(hess) %>% 
  rbind(hewlett) %>% 
  rbind(hilton) %>% 
  rbind(hindustan) %>% 
  rbind(hitachi) %>% 
  rbind(hna) %>% 
  rbind(hochteif) %>%
  rbind(hoechst) %>% 
  rbind(holcim) %>% 
  rbind(home_depot) %>% 
  rbind(hon_hai) %>% 
  rbind(honda) %>% 
  rbind(honeywell) %>% 
  rbind(household) %>%
  rbind(hp) %>%
  rbind(hsbc) %>%
  rbind(huawei) %>%
  rbind(humana) %>%
  rbind(husky) %>% 
  rbind(hutchinson) %>% 
  rbind(hypo) %>% 
  rbind(hyundai) 

write.csv(H,"H")

#Merging the datasets of companys that have a 10-k report starting with the latter I - ok
ii = rbind(iberdrola, ibm) %>% 
  rbind(ibp) %>% 
  rbind(idemitsu) %>% 
  rbind(ikon) %>% 
  rbind(imp_chem) %>% 
  rbind(imp_tobacco) %>% 
  rbind(inbev) %>% 
  rbind(inchcape) %>% 
  rbind(indian_oil) %>% 
  rbind(inditex) %>% 
  rbind(ind_commercial) %>%  
  rbind(ineos) %>% 
  rbind(ing) %>%  
  rbind(ingram) %>%  
  rbind(intel) %>% 
  rbind(intl_airlines) %>% 
  rbind(intl_assets) %>% 
  rbind(intl_business) %>% 
  rbind(intl_paper) %>% 
  rbind(intl_petroleum) %>% 
  rbind(internationale_nederlanden) %>% 
  rbind(intesa_sanpaolo) %>% 
  rbind(intesabci) %>%
  rbind(invensys) %>% 
  rbind(israel) %>% 
  rbind(ist_sanpaolo) %>% 
  rbind(isuzu) %>% 
  rbind(itau) %>% 
  rbind(itausa) %>% 
  rbind(itochu) %>%
  rbind(itoyokado) %>%
  rbind(itt_hartford) %>%
  rbind(itt_industries)

write.csv(ii,"ii")

#Merging the datasets of companys that have a 10-k report starting with the latter J - ok
J = rbind(jsainsbury, jcpenney) %>% 
  rbind(jp_morgan) %>% 
  rbind(japan_airlines) %>% 
  rbind(japan_energy) %>% 
  rbind(japan_post) %>% 
  rbind(japan_telecom) %>% 
  rbind(japan_tobacco) %>% 
  rbind(jardine_matheson) %>% 
  rbind(jbs) %>% 
  rbind(jd.com) %>% 
  rbind(jfe) %>%  
  rbind(jiangxi) %>% 
  rbind(john_hancock) %>%  
  rbind(johnson) %>%  
  rbind(johnson_controls) %>% 
  rbind(jusco) %>% 
  rbind(jx_holdings)

write.csv(J,"J")

#Merging the datasets of companys that have a 10-k report starting with the latter K - ok
K = rbind(kajima, kansai) %>% 
  rbind(kawasaki) %>% 
  rbind(kawasaki_steel) %>% 
  rbind(kb_fin) %>% 
  rbind(kbc) %>% 
  rbind(kddi) %>% 
  rbind(kfw) %>% 
  rbind(kia) %>% 
  rbind(kimberly) %>% 
  rbind(kingfisher) %>% 
  rbind(kirin) %>%  
  rbind(kirin_holdings) %>% 
  rbind(kmart) %>%  
  rbind(kobe) %>%  
  rbind(koc) %>% 
  rbind(kohls) %>% 
  rbind(komatsu) %>% 
  rbind(koninklijke) %>% 
  rbind(kookmin) %>% 
  rbind(korea) %>% 
  rbind(kraft) %>% 
  rbind(kreditanstalt) %>% 
  rbind(kroger) %>%
  rbind(kt) %>% 
  rbind(kubota) %>% 
  rbind(kumagai) %>% 
  rbind(kvarner) %>% 
  rbind(kyocera) %>% 
  rbind(kyushu)

write.csv(K,"K")
  
#Merging the datasets of companys that have a 10-k report starting with the latter L
L = rbind(lm_ericsson, loreal) %>% 
  rbind(ladbrokes) %>% 
  rbind(lafarge) %>% 
  rbind(lafargeholcim) %>% 
  rbind(lagardere) %>% 
  rbind(lair) %>% 
  rbind(landesbank) %>% 
  rbind(lear) %>% 
  rbind(legal_general) %>% 
  rbind(lehman_brothers) %>% 
  rbind(lennar) %>%  
  rbind(lenovo) %>% 
  rbind(lg) %>%  
  rbind(lg_elect) %>%  
  rbind(liberty_holding) %>% 
  rbind(liberty_mutual) %>% 
  rbind(lloyds) %>% 
  rbind(lloyds_tsb) %>% 
  rbind(lockheed) %>% 
  rbind(loews) %>% 
  rbind(louis) %>% 
  rbind(lowes) %>% 
  rbind(lucent) %>% 
  rbind(lufthansa) %>% 
  rbind(lukoil) %>% 
  rbind(lvmh) %>% 
  rbind(lyondell) %>% 
  rbind(lyondellbasell) %>% 
  rbind(lyonnaise) 

write.csv(L,"L")

#Merging the datasets of companys that have a 10-k report starting with the latter M
M = rbind(macys, maersk) %>% 
  rbind(magna) %>% 
  rbind(man) %>% 
  rbind(mannesmann) %>% 
  rbind(manpower) %>% 
  rbind(manulife) %>% 
  rbind(mapfre) %>% 
  rbind(marathon_oil) %>% 
  rbind(marathon_petroleum) %>% 
  rbind(marks) %>% 
  rbind(marquard) %>%  
  rbind(marriott) %>% 
  rbind(marsh) %>%  
  rbind(marubeni) %>%  
  rbind(masco) %>% 
  rbind(massachsetts) %>% 
  rbind(matsushita) %>% 
  rbind(matsushita_works) %>% 
  rbind(mazda) %>% 
  rbind(mbna) %>% 
  rbind(mcdonalds) %>% 
  rbind(mcdonnell) %>% 
  rbind(mci_com) %>%
  rbind(mci_worldcom) %>% 
  rbind(mckesson) %>% 
  rbind(medco) %>% 
  rbind(mediceo) %>% 
  rbind(meiji) %>% 
  rbind(melville) %>%
  rbind(mercantil) %>% 
  rbind(merck) %>% 
  rbind(merril_lynch) %>% 
  rbind(gerdau) %>% 
  rbind(metlife) %>% 
  rbind(metro) %>% 
  rbind(metropolitan) %>%  
  rbind(michelin) %>% 
  rbind(microsoft) %>%  
  rbind(minnesota) %>%  
  rbind(mirant) %>% 
  rbind(mitsubishi) %>% 
  rbind(mitsubishi_elect) %>% 
  rbind(mitsubishi_heavy) %>% 
  rbind(mitsubishi_materials) %>% 
  rbind(mitsubishi_motors) %>% 
  rbind(mitsubishi_tokyo) %>% 
  rbind(mitsubishi_ufj) %>% 
  rbind(mitsui) %>%
  rbind(mitsui_fudosan) %>% 
  rbind(mitsui_life) %>% 
  rbind(mitsui_marine) %>% 
  rbind(mitsui_osk) %>% 
  rbind(mitsui_sumitomo) %>% 
  rbind(mitsukoshi) %>%
  rbind(mittal) %>% 
  rbind(mizuho) %>%
  rbind(mizuho_holdings) %>%
  rbind(mobil) %>% 
  rbind(moller) %>%
  rbind(mondelez) %>%
  rbind(monsanto) %>%
  rbind(montedison) %>%
  rbind(morgan_stanley) %>%
  rbind(morgan_stanley_grp) %>%
  rbind(morrisons) %>%
  rbind(motorola) %>%
  rbind(ms_ad) %>%
  rbind(munchener) %>%
  rbind(munich_re) %>%
  rbind(murphy)

write.csv(M,"M")

#Merging the datasets of companys that have a 10-k report starting with the latter N
N = rbind(nabisco, national_ausbank) %>% 
  rbind(national_grid) %>% 
  rbind(national_westminster) %>% 
  rbind(nationsbank) %>% 
  rbind(nationwide) %>% 
  rbind(nationwide_bldg) %>% 
  rbind(nationwide_ins) %>% 
  rbind(nec) %>% 
  rbind(neste) %>% 
  rbind(nestle) %>% 
  rbind(new_china) %>%  
  rbind(ny_ins) %>% 
  rbind(news) %>%  
  rbind(nextel) %>%  
  rbind(nichimen) %>% 
  rbind(nike) %>% 
  rbind(nippon_exp) %>% 
  rbind(nippon_ins) %>% 
  rbind(nippon_mining) %>% 
  rbind(nippon_oil) %>% 
  rbind(nippon_paper) %>% 
  rbind(nippon_steel) %>% 
  rbind(nippon_tel) %>%
  rbind(nippon_yusen) %>% 
  rbind(nippondenso) %>% 
  rbind(nissan) %>% 
  rbind(nissho) %>% 
  rbind(nkk) %>% 
  rbind(noble) %>%
  rbind(nokia) %>% 
  rbind(nomura) %>% 
  rbind(norddeutsche) %>% 
  rbind(nordea) %>% 
  rbind(norinchukin) %>% 
  rbind(norsk) %>% 
  rbind(nortel) %>%  
  rbind(northern) %>% 
  rbind(northrop) %>%  
  rbind(northwest_airlines) %>%  
  rbind(northwestern) %>% 
  rbind(norwest) %>% 
  rbind(norwich) %>% 
  rbind(novartis) %>% 
  rbind(nucor) %>% 
  rbind(nynex) 

write.csv(N,"N")

#Merging the datasets of companys that have a 10-k report starting with the latter O - ok
O = rbind(oao_gazprom, oao_lukoil) %>% 
  rbind(obayashi) %>% 
  rbind(occidental) %>% 
  rbind(office_depot) %>% 
  rbind(officemax) %>% 
  rbind(oil_natural) %>% 
  rbind(oji_paper) %>% 
  rbind(old_mutual) %>% 
  rbind(olivetti) %>% 
  rbind(omv) %>% 
  rbind(onex) %>%  
  rbind(oracle) %>% 
  rbind(orange) 

write.csv(O,"O")

#Merging the datasets of companys that have a 10-k report starting with the latter P
p1 = rbind(paccar, pacific_gas) %>% 
  rbind(pacific_telesis) %>% 
  rbind(pacificare) %>% 
  rbind(panasonic) %>% 
  rbind(pdvsa) %>% 
  rbind(pechiney) %>% 
  rbind(pemex) %>% 
  rbind(peninsular) %>% 
  rbind(peoples_ins) %>% 
  rbind(pepsico) %>% 
  rbind(peregrine) %>%  
  rbind(pertamina) %>% 
  rbind(petrobras) %>%  
  rbind(petrocanada) %>%  
  rbind(petrofina) %>% 
  rbind(petronas) %>% 
  rbind(petroplus) %>% 
  rbind(peugeot) %>% 
  rbind(pfizer) %>% 
  rbind(pge) %>% 
  rbind(pharmacia) %>% 
  rbind(phillip_morris) %>% 
  rbind(phillips_elect) %>%
  rbind(phillips66) %>% 
  rbind(pinault) %>% 
  rbind(ping_an) %>% 
  rbind(pkn) %>% 
  rbind(plains_all) %>% 
  rbind(plains_holdings) %>%
  rbind(pnc) %>% 
  rbind(pohang) %>% 
  rbind(posco) %>% 
  rbind(power_can) %>% 
  rbind(ppr) %>% 
  rbind(premcor) %>% 
  rbind(preussag) %>%  
  rbind(price) %>% 
  rbind(procter) %>%  
  rbind(progressive) %>%  
  rbind(prudential) %>% 
  rbind(prudential_fin) %>% 
  rbind(prudential_ins) %>% 
  rbind(pt) %>% 
  rbind(ptt) %>% 
  rbind(public_serv) %>% 
  rbind(publix) %>% 
  rbind(pulte) 

write.csv(p1,"p1")

#Merging the datasets of companys that have a 10-k report starting with the latter Q
Q = rbind(qualcomm, quanta) %>% 
  rbind(qwest)
  
write.csv(Q,"Q")

#Merging the datasets of companys that have a 10-k report starting with the latter R
R = rbind(rj, rabobank) %>% 
  rbind(rag) %>% 
  rbind(randstad) %>% 
  rbind(rao) %>% 
  rbind(raytheon) %>% 
  rbind(reliance) %>% 
  rbind(reliant) %>%
  rbind(reliant_res) %>%
  rbind(renault) %>% 
  rbind(repsol) %>% 
  rbind(rep_industries) %>% 
  rbind(research) %>%  
  rbind(resona) %>% 
  rbind(rexel) %>%  
  rbind(ricoh) %>%  
  rbind(rio_tinto) %>%
  rbind(rite_aid) %>% 
  rbind(rjr) %>% 
  rbind(robert_bosch) %>% 
  rbind(roche) %>% 
  rbind(roche_holding) %>% 
  rbind(rockwell) %>% 
  rbind(rolls_royce) %>% 
  rbind(royal_sun) %>% 
  rbind(royal_sun_grp) %>%
  rbind(royal_ahold) %>% 
  rbind(royal_bank_can) %>% 
  rbind(royal_scotland) %>% 
  rbind(royal_dutch) %>% 
  rbind(royal_ins) %>% 
  rbind(royal_kpn) %>%
  rbind(royal_mail) %>% 
  rbind(royal_philips) %>% 
  rbind(royal_ptt) %>% 
  rbind(ruhrkohle) %>% 
  rbind(rwe)
  
write.csv(R,"R")

#Merging the datasets of companys that have a 10-k report starting with the latter S
S = rbind(sabmiller, safeway) %>% 
  rbind(salomon) %>% 
  rbind(samsung) %>% 
  rbind(san_paolo) %>% 
  rbind(sandoz) %>% 
  rbind(sanofi) %>% 
  rbind(santander) %>% 
  rbind(sanyo) %>% 
  rbind(sap) %>% 
  rbind(sara_lee) %>% 
  rbind(sberbank) %>%  
  rbind(sbc) %>% 
  rbind(schering) %>%  
  rbind(schlumberger) %>%  
  rbind(schneider) %>% 
  rbind(scottish_energy) %>% 
  rbind(scottish_power) %>% 
  rbind(sears_holdings) %>% 
  rbind(sears) %>% 
  rbind(seiko) %>% 
  rbind(sekisui) %>% 
  rbind(sekisui_house) %>% 
  rbind(seven) %>%
  rbind(sharp) %>% 
  rbind(shenhua) %>% 
  rbind(shimizu) %>% 
  rbind(shinhan) %>% 
  rbind(showa) %>% 
  rbind(siemens) %>%
  rbind(sinopec) %>% 
  rbind(sinopharm) %>% 
  rbind(sistema) %>% 
  rbind(sk) %>% 
  rbind(sk_holdings) %>% 
  rbind(skandia) %>% 
  rbind(skanska) %>%  
  rbind(smithkline) %>% 
  rbind(snow) %>%  
  rbind(societe_generale) %>%  
  rbind(sodexho) %>% 
  rbind(softbank) %>% 
  rbind(softbank_group) %>% 
  rbind(soil) %>% 
  rbind(solectron) %>% 
  rbind(solvay) %>% 
  rbind(sompo_holdings) %>% 
  rbind(sompo_ins) %>% 
  rbind(sompo_nipponkoa) %>%
  rbind(sony) %>% 
  rbind(southern_comp) %>% 
  rbind(sprint) %>% 
  rbind(sse) %>% 
  rbind(stpaul) %>% 
  rbind(standard) %>%
  rbind(standard_life) %>% 
  rbind(staples) %>%
  rbind(state_bank) %>%
  rbind(state_farm) %>% 
  rbind(state_grid) %>%
  rbind(statoil) %>%
  rbind(stora) %>%
  rbind(strabag) %>%
  rbind(subaru) %>%
  rbind(suez_environment) %>%
  rbind(suez_lyonnaise) %>%
  rbind(sumikin) %>%
  rbind(sumitomo) %>%
  rbind(sumitomo_corp) %>%
  rbind(sumitomo_elect) %>%
  rbind(sumitomo_life) %>%
  rbind(sumitomo_metal) %>%
  rbind(sum_mitsui_bank) %>%
  rbind(sum_mitsui_fin) %>%
  rbind(sun_life) %>%
  rbind(sun_life_fin) %>% 
  rbind(sun_micro) %>%
  rbind(suncor) %>%
  rbind(sunkyong) %>%
  rbind(sunoco) %>%
  rbind(suntory) %>%
  rbind(supervalu) %>%
  rbind(surgutneftegas) %>%
  rbind(suzuken) %>%
  rbind(suzuki) %>%
  rbind(svenksa) %>%
  rbind(swiss_bank) %>%
  rbind(swiss_life) %>%
  rbind(swiss_re) %>%
  rbind(swisscom) %>%
  rbind(sysco)
 
write.csv(S,"S")

#Merging the datasets of companys that have a 10-k report starting with the latter T
t = rbind(td, taikang) %>% 
  rbind(taisei) %>% 
  rbind(semiconductor) %>% 
  rbind(talanx) %>% 
  rbind(target) %>% 
  rbind(tata) %>% 
  rbind(tata_steel) %>% 
  rbind(teachers_ins) %>% 
  rbind(tech_data) %>% 
  rbind(telefonos) %>% 
  rbind(telecom_it) %>%
  rbind(telecomunicacoes) %>%  
  rbind(telefonaktiebolaget) %>% 
  rbind(telefonica) %>%  
  rbind(telstra) %>%  
  rbind(tencent) %>% 
  rbind(tenet) %>% 
  rbind(tenneco) %>%
  rbind(tesco) %>% 
  rbind(tesoro) %>% 
  rbind(teva) %>% 
  rbind(texaco) %>% 
  rbind(texas_inst) %>% 
  rbind(texas_utilities) %>% 
  rbind(textron) %>% 
  rbind(bank_tokyo) %>%
  rbind(british_pet) %>%
  rbind(broken_hill) %>% 
  rbind(chugoku) %>% 
  rbind(daiiichi_ins) %>% 
  rbind(fuji_bank) %>% 
  rbind(great_universal) %>% 
  rbind(industrial_bank) %>%
  rbind(longterm_bank) %>% 
  rbind(may_dpt) %>% 
  rbind(mitsubishi_bank) %>% 
  rbind(mitsubishi_trust) %>% 
  rbind(mitsui_trust) %>%
  rbind(nippon_credit) %>% 
  rbind(nomura_sec) %>% 
  rbind(norinchukin) %>%  
  rbind(principal_fin) %>% 
  rbind(principal_mutual) %>%  
  rbind(sakura_bank) %>%  
  rbind(sanwa_bank) %>% 
  rbind(seagram) %>% 
  rbind(standard_life) %>% 
  rbind(sumitomo_bank) %>% 
  rbind(sumitomo_trust) %>% 
  rbind(taiyo) %>% 
  rbind(tjx) %>% 
  rbind(tokai) %>% 
  rbind(tokio_marine) %>%
  rbind(tokyo_electric) %>% 
  rbind(williams) %>% 
  rbind(yasuda) %>% 
  rbind(yasuda_trust) %>% 
  rbind(thomson) %>% 
  rbind(thyssen) %>%
  rbind(time_warner) %>% 
  rbind(tnk) %>%
  rbind(tnt) %>%
  rbind(tohoku) %>% 
  rbind(tokio_marine_hldg) %>%
  rbind(tokyo_gas) %>%
  rbind(tokyu) %>%
  rbind(tomen) %>%
  rbind(tonen) %>%
  rbind(toppan) %>%
  rbind(toray) %>%
  rbind(toronto) %>%
  rbind(tosco) %>%
  rbind(toshiba) %>%
  rbind(total) %>%
  rbind(toyota) %>%
  rbind(toyota_tsusho) %>%
  rbind(tpg) %>%
  rbind(tractebel) %>%
  rbind(transcanada) %>%
  rbind(travelers) %>% 
  rbind(trw) %>%
  rbind(tui) %>%
  rbind(twentyfirst) %>%
  rbind(tyco) %>%
  rbind(tyson)
    
write.csv(t,"t")
  
#Merging the datasets of companys that have a 10-k report starting with the latter T
U = rbind(us_west, us_bancorp) %>% 
    rbind(us_postal) %>% 
    rbind(ual) %>% 
    rbind(ubs) %>% 
    rbind(ubs_group) %>% 
    rbind(ufj_hldgs) %>% 
    rbind(ultramar) %>% 
    rbind(ultrapar) %>% 
    rbind(unicredit) %>% 
    rbind(unicredito) %>% 
    rbind(unilever) %>%  
    rbind(union_bank) %>% 
    rbind(unionpacific) %>%  
    rbind(uniper) %>%  
    rbind(unipol) %>% 
    rbind(unitedhealth_corp) %>% 
    rbind(united_parcel) %>% 
    rbind(united_serv) %>% 
    rbind(us_postal) %>% 
    rbind(us_steel) %>% 
    rbind(united_tech) %>% 
    rbind(unitedhealth_grp) %>% 
    rbind(upm) %>%
    rbind(ups) %>% 
    rbind(us_foods) %>% 
    rbind(usaa) %>% 
    rbind(usinor) %>% 
    rbind(usx) 
    
write.csv(U,"U")

#Merging the datasets of companys that have a 10-k report starting with the latter V
V = rbind(vale, valero) %>% 
  rbind(vattenfall) %>% 
  rbind(veolia) %>% 
  rbind(verizon) %>% 
  rbind(viacom) %>% 
  rbind(vinci) %>% 
  rbind(visteon) %>% 
  rbind(vivendi) %>% 
  rbind(vodafone) %>% 
  rbind(volkswagen) %>% 
  rbind(volvo) %>%  
  rbind(vtb) 

write.csv(V,"V")

#Merging the datasets of companys that have a 10-k report starting with the latter 
W = rbind(wachovia, walgreen) %>% 
  rbind(walmart) %>% 
  rbind(warner_lambert) %>% 
  rbind(washington_mutual) %>% 
  rbind(waste) %>% 
  rbind(well) %>% 
  rbind(wells_fargo) %>% 
  rbind(wesfarmers) %>% 
  rbind(westj_rail) %>% 
  rbind(westdeutsche) %>% 
  rbind(westinghouse) %>%  
  rbind(westlb) %>% 
  rbind(westpac) %>%  
  rbind(weyerhaeuser) %>%  
  rbind(wh) %>% 
  rbind(whirlpool) %>% 
  rbind(william_hill) %>% 
  rbind(wilmar) %>% 
  rbind(winndixie) %>% 
  rbind(winterthur) %>% 
  rbind(wmx) %>% 
  rbind(wistron) %>% 
  rbind(wolseley) %>%
  rbind(woolworths) %>% 
  rbind(world_fuel) %>% 
  rbind(worldcom) %>% 
  rbind(wyeth) 

write.csv(W,"W")

#Merging the datasets of companys that have a 10-k report starting with the latter X
X = rbind(xcel, xerox) %>% 
  rbind(xstrata)
  
write.csv(X,"X")

#Merging the datasets of companys that have a 10-k report starting with the latter Y
Y = rbind(yamada, yamaha) %>% 
  rbind(yankuang)
  
write.csv(Y,"Y")

#Merging the datasets of companys that have a 10-k report starting with the latter Z
Z = rbind(zf, zhejiang) %>% 
  rbind(zurich_fin) %>% 
  rbind(zurich_ins) 

write.csv(Z,"Z")

#Merging all the datasets into one 
cik_dataset = rbind(A, B) %>%
  rbind(C) %>%
  rbind(D) %>%
  rbind(E) %>%
  rbind(f) %>%
  rbind(G) %>%
  rbind(H) %>%
  rbind(ii) %>%
  rbind(J) %>%
  rbind(L) %>%
  rbind(M) %>%
  rbind(N) %>%
  rbind(O) %>%
  rbind(p1) %>%
  rbind(Q) %>%
  rbind(R) %>%
  rbind(S) %>%
  rbind(t) %>% 
  rbind(U) %>% 
  rbind(V) %>% 
  rbind(W) %>% 
  rbind(X) %>% 
  rbind(Y) %>% 
  rbind(Z)

write.csv(cik_dataset, "cik_dataset") 


  



