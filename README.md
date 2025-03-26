# Arma 3 RHS Warlords Config

Configuration with RHS vehicles and infantry for Warlords Arma 3 modes
Steam Workshop: https://steamcommunity.com/sharedfiles/filedetails/?id=3451728962

![Frame 2](https://github.com/user-attachments/assets/3d422659-2cfa-44d3-9f97-2557cf86aaeb)

Config in Description.ext:

```
class CfgWLRequisitionPresets
{
    class WARLORDS_RVNWP_RHS_CLASS
    {

        class WEST
        {

            // Пехота
            class Infantry
            {   
                class rhsusf_usmc_marpat_wd_gunner { cost = 10; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_driver { cost = 10; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_crewman { cost = 10; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_grenadier { cost = 25; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_machinegunner { cost = 25; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_explosives { cost = 25; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_officer { cost = 50; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_marksman { cost = 75; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_stinger { cost = 75; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_smaw { cost = 75; requirements[]={}; };
                class rhsusf_usmc_marpat_wd_riflemanat { cost = 75; requirements[]={}; };
            };

            // Снаряжение (Ящики)
            class Gear
            {
                class rhsusf_mags_crate { cost = 200; requirements[]={}; };
                class rhsusf_weapon_crate { cost = 200; requirements[]={}; };
                class rhsusf_launcher_crate { cost = 200; requirements[]={}; };
                class rhsusf_spec_weapons_crate { cost = 200; requirements[]={}; };
                class rhsusf_gear_crate { cost = 200; requirements[]={}; };
            };

            // Гавань
            class Naval
            {
                class B_Boat_Transport_01_F { cost = 250; requirements[]={"W"}; };
            };

            // Минометы, станочные орудия
            class Defences
            {
                class RHS_M2StaticMG_MiniTripod_USMC_WD { cost = 300; requirements[]={}; };
                class RHS_M2StaticMG_USMC_WD { cost = 350; requirements[]={}; };
                class B_G_HMG_02_high_F { cost = 400; requirements[]={}; };
                class RHS_MK19_TriPod_USMC_WD { cost = 600; requirements[]={}; };
                class B_static_AT_F { cost = 900; requirements[]={}; };
                class RHS_TOW_TriPod_USMC_WD { cost = 1700; requirements[]={}; };
                class ace_dragon_staticAssembled { cost = 2000; requirements[]={}; };
                class RHS_M252_WD { cost = 3000; requirements[]={}; };
                class RHS_Stinger_AA_pod_USMC_WD { cost = 3500; requirements[]={}; };
                class RHS_M119_WD { cost = 4000; requirements[]={}; };
                
            };

            // Авиация
            class Aircraft
            {
                // Истрибители
                class rhsusf_f22 { cost = 6000; requirements[]={"A"}; };
                class RHS_A10 { cost = 7000; requirements[]={"A"}; };
                class RHS_C130J_Cargo { cost = 8000; requirements[]={"A"}; };
                class RHS_C130J { cost = 9000; requirements[]={"A"}; };

                // Вертолеты
                class rhs_uh1h_hidf_unarmed { cost = 2200; requirements[]={"H"}; };
                class RHS_UH60M { cost = 2700; requirements[]={"H"}; };
                class RHS_UH1Y { cost = 2700; requirements[]={"H"}; };
                class RHS_CH_47F { cost = 3600; requirements[]={"H"}; };
                class RHS_MELB_AH6M { cost = 4200; requirements[]={"H"}; };
                class rhsusf_CH53E_USMC { cost = 4700; requirements[]={"H"}; };
                class RHS_AH64D_wd { cost = 5500; requirements[]={"H"}; };
            };
            
            // Техника
            class Vehicles
            {   
                // Машины
                class rhsusf_m998_w_s_4dr { cost = 25; requirements[]={}; };
                class rhsusf_m998_w_s_4dr_halftop { cost = 30; requirements[]={}; };
                class rhsusf_m998_w_s_2dr_halftop { cost = 30; requirements[]={}; };
                class rhsusf_m998_w_s_4dr_fulltop { cost = 50; requirements[]={}; };
                class rhsusf_m998_w_s_2dr_fulltop { cost = 50; requirements[]={}; };

                class rhsusf_m1025_w_s { cost = 100; requirements[]={}; };
                class rhsusf_m1025_w_s_m2 { cost = 125; requirements[]={}; };
                class rhsusf_m1025_w_s_Mk19 { cost = 150; requirements[]={}; };
                class rhsusf_m966_w { cost = 175; requirements[]={}; };

                class rhsusf_m1152_usmc_wd { cost = 125; requirements[]={}; };
                class rhsusf_m1165_usmc_wd { cost = 130; requirements[]={}; };
                class rhsusf_m1152_rsv_usmc_wd { cost = 150; requirements[]={}; };
                class rhsusf_m1151_usmc_wd { cost = 175; requirements[]={}; };
                class rhsusf_m1152_sicps_usarmy_wd { cost = 100; requirements[]={}; };
                class rhsusf_m1151_m2crows_usmc_wd { cost = 225; requirements[]={}; };
                class rhsusf_m1151_mk19crows_usmc_wd { cost = 250; requirements[]={}; };
                class rhsusf_m1151_m2_v3_usmc_wd { cost = 275; requirements[]={}; };
                class rhsusf_m1151_mk19_v3_usmc_wd { cost = 300; requirements[]={}; };

                class rhsusf_CGRCAT1A2_usmc_wd { cost = 340; requirements[]={}; };
                class rhsusf_CGRCAT1A2_M2_usmc_wd { cost = 380; requirements[]={}; };
                class rhsusf_CGRCAT1A2_Mk19_usmc_wd { cost = 420; requirements[]={}; };
                class rhsusf_M1232_MC_M2_usmc_wd { cost = 450; requirements[]={}; };

                class rhsusf_m1240a1_m2_usmc_wd { cost = 475; requirements[]={}; };
                class rhsusf_m1240a1_m240_usmc_wd { cost = 500; requirements[]={}; };
                class rhsusf_m1240a1_m2crows_usmc_wd { cost = 525; requirements[]={}; };
                class rhsusf_m1240a1_mk19crows_usmc_wd { cost = 550; requirements[]={}; };

                // Грузовики
                class rhsusf_M1078A1P2_WD_flatbed_fmtv_usarmy { cost = 260; requirements[]={}; };
                class rhsusf_M1078A1P2_WD_fmtv_usarmy { cost = 280; requirements[]={}; };
                class rhsusf_M142_usarmy_WD { cost = 1200; requirements[]={}; };

                class rhsusf_M1084A1P2_WD_fmtv_usarmy { cost = 320; requirements[]={}; };
                class rhsusf_M1085A1P2_B_WD_Medical_fmtv_usarmy { cost = 340; requirements[]={}; };

                class rhsusf_M977A4_usarmy_wd { cost = 400; requirements[]={}; };
                class rhsusf_M977A4_AMMO_usarmy_wd { cost = 440; requirements[]={}; };
                class rhsusf_M977A4_REPAIR_usarmy_wd { cost = 440; requirements[]={}; };
                class rhsusf_M978A4_usarmy_wd { cost = 440; requirements[]={}; };

                // БТР
                class rhsusf_m113_usarmy_unarmed { cost = 600; requirements[]={}; };
                class rhsusf_m113_usarmy_medical { cost = 650; requirements[]={}; };
                class rhsusf_m113_usarmy_supply { cost = 700; requirements[]={}; };
                class rhsusf_m113_usarmy_M240 { cost = 750; requirements[]={}; };
                class rhsusf_m113_usarmy { cost = 850; requirements[]={}; };
                class rhsusf_m113_usarmy_MK19 { cost = 920; requirements[]={}; };

                class rhsusf_M1117_W { cost = 1000; requirements[]={}; };

                class rhsusf_stryker_m1126_m2_wd { cost = 1100; requirements[]={}; };
                class rhsusf_stryker_m1126_mk19_wd { cost = 1200; requirements[]={}; };
                class rhsusf_stryker_m1132_m2_np_wd { cost = 1300; requirements[]={}; };
                class rhsusf_stryker_m1127_m2_wd { cost = 1400; requirements[]={}; };
                class rhsusf_stryker_m1132_m2_wd { cost = 1500; requirements[]={}; };
                class rhsusf_stryker_m1134_wd { cost = 1600; requirements[]={}; };

                // БМП
                class RHS_M2A2_wd { cost = 2000; requirements[]={}; };
                class RHS_M2A3_wd { cost = 2150; requirements[]={}; };
                class RHS_M6_wd { cost = 2300; requirements[]={}; };
                class RHS_M2A3_BUSKI_wd { cost = 2450; requirements[]={}; };
                class RHS_M2A3_BUSKIII_wd { cost = 2700; requirements[]={}; };
                
                // ТАНКИ
                class rhsusf_m1a1aimwd_usarmy { cost = 3000; requirements[]={}; };
                class rhsusf_m1a1aim_tuski_wd { cost = 3700; requirements[]={}; };

                // ПВО
                class B_APC_Tracked_01_AA_F { cost = 2500; requirements[]={}; };

                // Самоходная Артилерия
                class rhsusf_m109_usarmy { cost = 3000; requirements[]={}; };

            };

        };

        class EAST
        {
            
            // Пехота
            class Infantry
            {   
                class rhs_msv_emr_rifleman { cost = 10; requirements[]={}; };
                class rhs_msv_emr_driver { cost = 10; requirements[]={}; };
                class rhs_msv_emr_crew { cost = 10; requirements[]={}; };
                class rhs_msv_emr_grenadier { cost = 25; requirements[]={}; };
                class rhs_msv_emr_machinegunner { cost = 25; requirements[]={}; };
                class rhs_msv_emr_engineer { cost = 25; requirements[]={}; };
                class rhs_msv_emr_efreitor { cost = 50; requirements[]={}; };
                class rhs_msv_emr_marksman { cost = 75; requirements[]={}; };
                class rhs_msv_emr_aa { cost = 75; requirements[]={}; };
                class rhs_msv_emr_at { cost = 75; requirements[]={}; };
                class rhs_msv_emr_LAT { cost = 75; requirements[]={}; };
                class rhs_vmf_emr_grenadier_rpg { cost = 75; requirements[]={}; };
            };

            // Снаряжение (Ящики)
            class Gear
            {
                class rhs_mags_crate { cost = 200; requirements[]={}; };
                class rhs_weapon_crate { cost = 200; requirements[]={}; };
                class rhs_launcher_crate { cost = 200; requirements[]={}; };
                class rhs_spec_weapons_crate { cost = 200; requirements[]={}; };
                class rhs_gear_crate { cost = 200; requirements[]={}; };
            };

            // Гавань
            class Naval
            {
                class O_Boat_Transport_01_F { cost = 250; requirements[]={"W"}; };
            };

            // Минометы, станочные орудия
            class Defences
            {
                class RHS_NSV_TriPod_MSV { cost = 250; requirements[]={}; };
                class rhs_KORD_MSV { cost = 300; requirements[]={}; };
                class rhs_KORD_high_MSV { cost = 350; requirements[]={}; };
                class RHS_ZU23_MSV { cost = 400; requirements[]={}; };
                class RHS_AGS30_TriPod_MSV { cost = 500; requirements[]={}; };
                class rhs_Metis_9k115_2_msv { cost = 600; requirements[]={}; };
                class rhs_Kornet_9M133_2_msv { cost = 700; requirements[]={}; };
                class rhs_SPG9M_MSV { cost = 750; requirements[]={}; };
                class rhs_Igla_AA_pod_msv { cost = 800; requirements[]={}; };
                class rhs_2b14_82mm_msv { cost = 2200; requirements[]={}; };
                class rhs_D30_msv { cost = 4000; requirements[]={}; };
            };

            // Авиация
            class Aircraft
            {
                // Истрибители
                class RHS_Su25SM_vvsc { cost = 6000; requirements[]={"A"}; };
                class rhs_mig29s_vvs { cost = 6500; requirements[]={"A"}; };
                class rhs_mig29sm_vvs { cost = 6500; requirements[]={"A"}; };
                class RHS_T50_vvs_generic_ext { cost = 7000; requirements[]={"A"}; };
                class RHS_TU95MS_vvs_old { cost = 9000; requirements[]={"A"}; };

                // Вертолеты
                class RHS_Mi8AMT_vvsc { cost = 2000; requirements[]={"H"}; };
                class rhs_ka60_grey { cost = 2500; requirements[]={"H"}; };
                class RHS_Mi8MTV3_heavy_vvsc { cost = 3000; requirements[]={"H"}; };
                class RHS_Mi24P_vvsc { cost = 4000; requirements[]={"H"}; };
                class RHS_Ka52_vvsc { cost = 4700; requirements[]={"H"}; };
                class rhs_mi28n_vvsc { cost = 5500; requirements[]={"H"}; };
            };

            // Техника
            class Vehicles
            {
                // Машины
                class rhs_uaz_open_MSV_01 { cost = 25; requirements[]={}; };
                class RHS_UAZ_MSV_01 { cost = 50; requirements[]={}; };
                
                class rhs_tigr_msv { cost = 100; requirements[]={}; };
                class rhs_tigr_sts_msv { cost = 200; requirements[]={}; };
                
                class rhsgref_BRDM2UM_msv { cost = 225; requirements[]={}; };
                class rhsgref_BRDM2_HQ_msv { cost = 250; requirements[]={}; };
                class rhsgref_BRDM2_msv { cost = 275; requirements[]={}; };
                class rhsgref_BRDM2_ATGM_msv { cost = 300; requirements[]={}; };

                // Грузовики
                class rhs_gaz66o_msv { cost = 80; requirements[]={}; };
                class rhs_gaz66_flat_msv { cost = 100; requirements[]={}; };
                class rhs_gaz66_ap2_msv { cost = 120; requirements[]={}; };
                class rhs_gaz66_r142_msv { cost = 120; requirements[]={}; };
                class rhs_gaz66_repair_msv { cost = 140; requirements[]={}; };
                class rhs_gaz66_ammo_msv { cost = 140; requirements[]={}; };
                class rhs_gaz66_zu23_msv { cost = 275; requirements[]={}; };

                class rhs_kraz255b1_bmkt_msv { cost = 150; requirements[]={}; };
                class rhs_kraz255b1_pmp_msv { cost = 150; requirements[]={}; };
                class rhs_kraz255b1_flatbed_msv { cost = 170; requirements[]={}; };
                class rhs_kraz255b1_fuel_msv { cost = 170; requirements[]={}; };

                class rhs_zil131_open_msv { cost = 160; requirements[]={}; };
                class rhs_zil131_msv { cost = 180; requirements[]={}; };

                class RHS_Ural_Open_MSV_01 { cost = 200; requirements[]={}; };
                class RHS_Ural_MSV_01 { cost = 220; requirements[]={}; };
                class RHS_Ural_Repair_MSV_01 { cost = 240; requirements[]={}; };
                class RHS_Ural_Fuel_MSV_01 { cost = 240; requirements[]={}; };
                class RHS_Ural_Zu23_MSV_01 { cost = 400; requirements[]={}; };
                class RHS_BM21_VV_01 { cost = 1500; requirements[]={}; };

                class rhs_kamaz5350_open_msv { cost = 260; requirements[]={}; };
                class rhs_kamaz5350_msv { cost = 280; requirements[]={}; };
                class rhs_kamaz5350_ammo_vv { cost = 300; requirements[]={}; };

                // БТР
                class rhs_btr60_msv { cost = 1000; requirements[]={}; };
                class rhs_btr70_msv { cost = 1400; requirements[]={}; };
                class rhs_btr80_msv { cost = 1900; requirements[]={}; };
                class rhs_btr80a_msv { cost = 2400; requirements[]={}; };

                // БМП
                class rhs_bmp1_msv { cost = 1400; requirements[]={}; };
                class rhs_bmp2d_msv { cost = 1700; requirements[]={}; };
                class rhs_bmp2k_msv { cost = 1800; requirements[]={}; };
                class rhs_bmp3_msv { cost = 2400; requirements[]={}; };

                // ТАНКИ
                class rhs_t72ba_tv { cost = 2200; requirements[]={}; };
                class rhs_sprut_vdv { cost = 2500; requirements[]={}; };
                class rhs_t80b { cost = 3000; requirements[]={}; };
                class rhs_t80a { cost = 3100; requirements[]={}; };
                class rhs_t80uk { cost = 3200; requirements[]={}; };
                class rhs_t90_tv { cost = 4000; requirements[]={}; };
                class rhs_t14_tv { cost = 5000; requirements[]={}; };

                // ПВО
                class rhs_zsu234_aa { cost = 2500; requirements[]={}; };

                // Самоходная Артилерия
                class rhs_2s1_vmf { cost = 3000; requirements[]={}; };
                class rhs_9k79_B { cost = 25000; requirements[]={}; };

            };
        };
    };
};

// Перезапись цен
class CfgWLAssetCostOverride
{
	Scan = 250;				// Сканирование
	Airdrop = 1;			// Цена вызова техники с неба
	FastTravel = 75;		// Быстрое перемещение
	LastLoadout = 200;		// Последняя экипировка
	Arsenal = 200;			// Вызов Арсенала
	FundsTransfer = 0;	    // Перевод средств
	ResetVoting = 0;		// Сброс голосования
};
```
