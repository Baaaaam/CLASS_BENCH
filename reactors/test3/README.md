Test 1 : Single reactor over 120 years
=============================================

120 years simulation, single reactor, fixed fuel recipe: reactor power, fuel burnup and associated recipes, (re)fueling strategy

Definition
----------------
120 year simulation, single reactor, fixed fuel recipe, 120 years operation

Reactor : 
* Type: LWR, 
* **Fuel**: UOX 3.25%w enriched uranium, 
* **Mass**: 82 tons (Oxyde Metal),
* **Thermal Power**: 2875e6 W -- **Efficiency**: 34%,  
* **Discharge burn-up** : 43.03 GWd/t -- Full Cycle length 3y, 
* **Capacity factor**: 1, 
* **Suggested recipes**:
  * **Fresh UOX** :
    * <sup>235</sup>U   :    3.25%w
    * <sup>238</sup>U   :   96.75%w
    * <sup>16</sup>O    :   13.44%w \
    * the %w are normalized to the quantity of uranium... but because the reactor fuel mass is given in oxyde metal, one provides also the corresponding oxygen quantity

  * **Used UOX** @43.03 GWd/t (atomic ratio): total mass = 69.27 tHM
    * <sup>234</sup>U   :  2.88551e-06
    * <sup>235</sup>U   :   0.00573857
    * <sup>236</sup>U   :   0.00452986
    * <sup>238</sup>U   :     0.977249
    * <sup>237</sup>Np  :  0.000575072
    * <sup>238</sup>Pu  :  0.000251141
    * <sup>239</sup>Pu  :   0.00593915
    * <sup>240</sup>Pu  :   0.00270459
    * <sup>241</sup>Pu  :   0.00174216
    * <sup>242</sup>Pu  :  0.000902859
    * <sup>241</sup>Am  :  4.36865e-05
    * <sup>242</sup>Am+ :  8.81985e-07
    * <sup>243</sup>Am  :  0.000206983
    * <sup>242</sup>Cm  :  2.2778e-05 
    * <sup>243</sup>Cm  :  5.91655e-07
    * <sup>244</sup>Cm  :  8.44813e-05
    * <sup>245</sup>Cm  :  5.38651e-06

