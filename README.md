# bug
bug
Log uploaded on Saturday, January 8, 2022, 11:12:53 AM
Loaded mods:
Harmony(brrainz.harmony)[mv:1.2.0.0]: 0Harmony(2.2.0), HarmonyMod(1.2.0)
Core(Ludeon.RimWorld): (no assemblies)
HugsLib(UnlimitedHugs.HugsLib)[ov:9.0.1]: 0Harmony(av:2.2.0,fv:1.2.0.1), HugsLib(av:1.0.0,fv:9.0.1)
Humanoid Alien Races(erdelf.HumanoidAlienRaces): 0Harmony(2.2.0), AlienRace(1.0.0)
RJW-边缘工作世界(RimJobWorld)
(rim.job.world)[mv:4.8.1.2]: 0MultiplayerAPI(av:0.2.0,fv:0.1.0), RJW(0.0.0)
RJW-边缘工作世界扩展(RimJobWorld Extension)(rimworld.ekss.rjwex)[mv:1.3.2]: 0MultiplayerAPI(av:0.2.0,fv:0.1.0), RimJobWorldExtension(1.0.0)
RJW-事件(RJW-Events)(c0ffee.rjw.events)[mv:0.1.1]: RJW-Events(0.0.0)
Rimworld-Animations(c0ffee.rimworld.animations)[mv:1.2.5]: Rimworld-Animations(1.0.0)
RJW-动画-新动画(RJWAnimAddons-XtraAnims)(Tory187.RJWAnimAddons.XtraAnims)[mv:0.2.9]: (no assemblies)

Active Harmony patches:
AddictionUtility.CanBingeOnNow: post: AlienRace.HarmonyPatches.CanBingeNowPostfix
AgeInjuryUtility.GenerateRandomOldAgeInjuries: PRE: AlienRace.HarmonyPatches.GenerateRandomOldAgeInjuriesPrefix
AgeInjuryUtility.RandomHediffsToGainOnBirthday: post: AlienRace.HarmonyPatches.RandomHediffsToGainOnBirthdayPostfix
Alert_LifeThreateningHediff.GetExplanation: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BackCompatibilityConverter_0_18.PostExposeData: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BattleLogEntry_DamageTaken.DamagedBody: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BattleLogEntry_ExplosionImpact.DamagedBody: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BattleLogEntry_MeleeCombat.DamagedBody: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BattleLogEntry_RangedImpact.DamagedBody: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
BedUtility.WillingToShareBed: post: AlienRace.HarmonyPatches.WillingToShareBedPostfix
Bed_Utility.in_same_bed: PRE: Rimworld_Animations.HarmonyPatch_JobDriver_InSameBedPatch.Prefix
Bill.PawnAllowedToStartAnew: post: AlienRace.HarmonyPatches.PawnAllowedToStartAnewPostfix
Building_Bed.DrawGUIOverlay: PRE: rjw.Building_Bed_Patch+Building_Bed_DrawGUIOverlay_Patch.Prefix
Building_Bed.GetGizmos: post: rjw.Building_Bed_Patch+Building_Bed_GetGizmos_Patch.Postfix
Building_Bed.GetInspectString: post: rjw.Building_Bed_Patch+Building_Bed_GetInspectString_Patch.Postfix
Building_Bed.get_DrawColorTwo: post: rjw.Building_Bed_Patch+Building_Bed_DrawColor_Patch.Postfix
CharacterCardUtility.DrawCharacterCard: TRANS: rjw.SexcardPatch.Transpiler
CompAbilityEffect_WordOfLove.ValidateTarget: PRE: rjw.PATCH_CompAbilityEffect_WordOfLove_ValidateTarget.GenderChecks
CompAssignableToPawn.get_AssigningCandidates: post: AlienRace.HarmonyPatches.AssigningCandidatesPostfix
CompDrug.PostIngested: post: AlienRace.HarmonyPatches.PostIngestedPostfix
CompRottable.StageChanged: PRE: AlienRace.HarmonyPatches.RottableCompStageChangedPostfix
CompTargetEffect_PsychicShock.DoEffectOn: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
CompUseEffect_InstallImplant.CanBeUsedBy: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
CompUseEffect_InstallImplant.DoEffect: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
CompUseEffect_InstallImplant.GetExistingImplant: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Corpse.GetInspectString: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Corpse.IngestedCalculateAmounts: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DamageWorker_AddInjury.ApplySmallPawnDamagePropagation: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DamageWorker_Blunt.<>c.<StunChances>b__2_0: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DamageWorker_Blunt.<>c.<StunChances>b__2_5: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DamageWorker_Blunt.ApplySpecialEffectsToPart: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugOutputsHealth.<>c__DisplayClass5_0.<Prosthetics>b__13: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugOutputsHealth.<>c__DisplayClass5_0.<Prosthetics>b__14: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugOutputsTextGen.<>c__DisplayClass0_5.<FlavorfulCombatTest>b__22: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugToolsPawns.Do10DamageUntilDead: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugTools_Health.Options_Damage_BodyParts: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugTools_Health.Options_Hediff_BodyParts: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
DebugWindowsOpener.DevToolStarterOnGUI: TRANS: HugsLib.Patches.DevToolStarterOnGUI_Patch.ExtendButtonsWindow
DebugWindowsOpener.DrawButtons: TRANS: HugsLib.Patches.DebugWindowsOpener_Patch.DrawAdditionalButtons
Designator.CanDesignateThing: post: AlienRace.HarmonyPatches.CanDesignateThingTamePostfix
Dialog_Options.DoWindowContents: TRANS: HugsLib.Patches.Dialog_Options_Patch.ReplaceModOptionsButton
EditWindow_Log.DoMessagesListing: PRE: HugsLib.Patches.EditWindow_Log_Patch.ExtraLogWindowButtons
EditWindow_TweakValues.DoWindowContents: TRANS: AlienRace.HarmonyPatches.TweakValuesTranspiler
EquipmentUtility.CanEquip: post: AlienRace.HarmonyPatches.CanEquipPostfix
Faction.FactionTick: TRANS: AlienRace.HarmonyPatches.FactionTickTranspiler
Faction.TryMakeInitialRelationsWith: post: AlienRace.HarmonyPatches.TryMakeInitialRelationsWithPostfix
FloatMenuMakerMap.CanTakeOrder: post: rjw.disable_FloatMenuMakerMap.NonHero_disable_controls
FloatMenuMakerMap.ChoicesAtFor: post: rjw.RMB_Menu.ChoicesAtFor
FoodUtility.AddThoughtsFromIdeo: PRE: AlienRace.HarmonyPatches.FoodUtilityAddThoughtsFromIdeoPrefix
FoodUtility.GetBodyPartNutrition: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
FoodUtility.ThoughtsFromIngesting: post: AlienRace.HarmonyPatches.ThoughtsFromIngestingPostfix
Game.DeinitAndRemoveMap: post: HugsLib.Patches.Game_DeinitAndRemoveMap_Patch.MapRemovalHook
Game.FillComponents: PRE: HugsLib.Patches.Game_FillComponents_Patch.GameInitializationHook
Game.FinalizeInit: post: HugsLib.Patches.Game_FinalizeInit_Patch.WorldLoadedHook
GameInitData.PrepForMapGen: PRE: AlienRace.HarmonyPatches.PrepForMapGenPrefix
GameRules.DesignatorAllowed: TRANS: AlienRace.HarmonyPatches.DesignatorAllowedTranspiler
GenConstruct.CanConstruct: post: AlienRace.HarmonyPatches.CanConstructPostfix
GlobalTextureAtlasManager.TryGetPawnFrameSet: PRE: AlienRace.HarmonyPatches.GlobalTextureAtlasGetFrameSetPrefix
GrammarUtility.RulesForPawn: post: AlienRace.HarmonyPatches.RulesForPawnPostfix
HarmonyPatches.DrawAddons: PRE: Rimworld_Animations.HarmonyPatch_AlienRace.Prefix_AnimateHeadAddons
HealthCardUtility.<>c__DisplayClass42_0.<DoDebugOptions>b__0: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HealthCardUtility.<>c__DisplayClass42_0.<DoDebugOptions>b__14: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HealthCardUtility.DrawOverviewTab: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HealthUtility.FixWorstHealthCondition: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HealthUtility.ShouldRandomSurgeryInjuriesAvoidDestroying: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Hediff.Tick: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffComp_DissolveGearOnDeath.Notify_PawnDied: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffComp_ReactOnDamage.React: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffGiver_Hypothermia.OnIntervalPassed: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffSet.<>c.<get_HasHead>b__11_0: post: AlienRace.HarmonyPatches.HasHeadPostfix
HediffSet.<GetNotMissingParts>d__41.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffSet.AddDirect: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffSet.CacheMissingPartsCommonAncestors: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
HediffSet.get_HasHead: PRE: AlienRace.HarmonyPatches.HasHeadPrefix
Hediff_Pregnant.DoBirthSpawn: PRE: rjw.PATCH_Hediff_Pregnant_DoBirthSpawn.on_begin_DoBirthSpawn
Hediff_Pregnant.Tick: PRE: rjw.PATCH_Hediff_Pregnant_Tick.abort_on_missing_genitals
ITab_Pawn_Gear.InterfaceDrop: PRE: rjw.PATCH_ITab_Pawn_Gear_InterfaceDrop.drop_locked_apparel
ITab_Pawn_Gear.TryDrawOverallArmor: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
InteractionWorker_RomanceAttempt.Interacted: TRANS: AlienRace.HarmonyPatches.RomanceAttemptInteractTranspiler
InteractionWorker_RomanceAttempt.SuccessChance: post: AlienRace.HarmonyPatches.RomanceAttemptSuccessChancePostfix
JobDriver.Cleanup: PRE: rjw.PATCH_JobDriver_DubsBadHygiene.cleanup_semen, rjw.PATCH_JobDriver_Loving_Cleanup.on_cleanup_driver
JobDriver_JoinInBed.MakeNewToils: post: Rimworld_Animations.HarmonyPatch_JobDriver_JoinInBed.Postfix
JobDriver_Lovin.GenerateRandomMinTicksToNextLovin: TRANS: AlienRace.HarmonyPatches.GenerateRandomMinTicksToNextLovinTranspiler
JobDriver_Lovin.MakeNewToils: PRE: rjw.PATCH_JobDriver_Lovin_MakeNewToils.lovin_patch_n_override
JobDriver_Mate.MakeNewToils: PRE: rjw.PATCH_JobDriver_Mate_MakeNewToils.matin_patch_n_override
JobDriver_Meditate.MeditationTick: PRE: rjw.PATCH_JobDriver_Meditate_MeditationTick.Disable_For_Nymph
JobDriver_Sex.PlaySexSound: PRE: Rimworld_Animations.HarmonyPatch_PlaySexSounds.Prefix
JobDriver_Sex.SexTick: PRE: Rimworld_Animations.HarmonyPatch_SexTick.Prefix
JobDriver_SexBaseInitiator.End: post: Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_End.Postfix
JobDriver_SexBaseInitiator.Start: post: Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_Start.Postfix
JobDriver_SexBaseRecieverLoved.MakeSexToil: TRANS: Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseReceiverLoved.Transpiler
JobDriver_Wear.Notify_Starting: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
JobDriver_Wear.TryUnequipSomething: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
JobGiver_Mate.TryGiveJob: post: rjw.PATCH_JobGiver_Mate_TryGiveJob.futa_animal_partner_search_patch
JobGiver_Meditate.TryGiveJob: post: rjw.PATCH_JobGiver_Meditate_TryGiveJob.Disable_For_Nymph
JobGiver_OptimizeApparel.ApparelScoreGain: post: AlienRace.HarmonyPatches.ApparelScoreGainPostFix TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
JobGiver_PrisonerGetDressed.FindGarmentCoveringPart: PRE: rjw.PATCH_JobGiver_PrisonerGetDressed_FindGarmentCoveringPart.prevent_locked_apparel_conflict
JobGiver_SatisfyChemicalNeed.DrugValidator: post: AlienRace.HarmonyPatches.DrugValidatorPostfix
LanguageDatabase.SelectLanguage: PRE: HugsLib.Patches.LanguageDatabase_Patch.ForceRestartAfterLangChange
Lord.RemovePawn: post: RJW_Events.HarmonyPatch_ReclotheOnRemovePawn.Postfix
LordJob_AssaultColony.CreateGraph: post: rjw.Patches_AssaultColonyForRape.Postfix
LordJob_Joinable_Party.ApplyOutcome: post: RJW_Events.HarmonyPatch_ReclotheOnEnd.Postfix
MainTabWindow_Research.DrawRightRect: TRANS: AlienRace.HarmonyPatches.ResearchScreenTranspiler
MainTabWindow_Research.ViewSize: TRANS: AlienRace.HarmonyPatches.ResearchScreenTranspiler
Map.ConstructComponents: post: HugsLib.Patches.Map_ConstructComponents_Patch.MapComponentsInitHook
Map.FinalizeInit: post: HugsLib.Patches.Map_FinalizeInit_Patch.MapLoadedHook
MapComponentUtility.MapGenerated: post: HugsLib.Patches.MapComponentUtility_MapGenerated_Patch.MapGeneratedHook
MedicalRecipesUtility.<GetFixedPartsToApplyOn>d__5.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
MemoryThoughtHandler.GetFirstMemoryOfDef: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.NumMemoriesOfDef: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.OldestMemoryOfDef: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.RemoveMemoriesOfDef: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.RemoveMemoriesOfDefIf: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.RemoveMemoriesOfDefWhereOtherPawnIs: PRE: AlienRace.HarmonyPatches.ThoughtReplacementPrefix
MemoryThoughtHandler.TryGainMemory: PRE: AlienRace.HarmonyPatches.TryGainMemoryPrefix
ModsConfig.RestartFromChangedMods: PRE: HugsLib.Patches.ModsConfig_RestartFromChangedMods_Patch.QuickRestartInDevMode
Page_ConfigureStartingPawns.CanDoNext: post: AlienRace.HarmonyPatches.CanDoNextStartPawnPostfix
Pawn.ChangeKind: PRE: AlienRace.HarmonyPatches.ChangeKindPrefix
Pawn.GetGizmos: post: [101]rjw.submit_button.add_button, [100]rjw.disable_Gizmos.NonHero_disable_gizmos, [99]rjw.Patch_AddSexGizmo.AddSexGizmo, [99]rjw.Rjw_buttons.add_designation_box, [99]rjw.Patch_AddGizmo.AddSemen_test
Pawn.SetFaction: post: AlienRace.HarmonyPatches.SetFactionPostfix
PawnApparelGenerator.GenerateStartingApparelFor: PRE: AlienRace.HarmonyPatches.GenerateStartingApparelForPrefix post: AlienRace.HarmonyPatches.GenerateStartingApparelForPostfix
PawnApparelGenerator.GenerateWorkingPossibleApparelSetFor: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnApparelGenerator.PossibleApparelSet.GiveToPawn: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnBioAndNameGenerator.FillBackstorySlotShuffled: PRE: AlienRace.HarmonyPatches.FillBackstoryInSlotShuffledPrefix TRANS: AlienRace.HarmonyPatches.FillBackstoryInSlotShuffledTranspiler
PawnBioAndNameGenerator.GeneratePawnName: PRE: AlienRace.HarmonyPatches.GeneratePawnNamePrefix
PawnBioAndNameGenerator.GiveAppropriateBioAndNameTo: post: AlienRace.HarmonyPatches.GiveAppropriateBioAndNameToPostfix
PawnBioAndNameGenerator.GiveShuffledBioTo: TRANS: AlienRace.HarmonyPatches.MinAgeForAdulthood
PawnBioAndNameGenerator.TryGetRandomUnusedSolidBioFor: post: AlienRace.HarmonyPatches.TryGetRandomUnusedSolidBioForPostfix
PawnBioAndNameGenerator.TryGiveSolidBioTo: TRANS: AlienRace.HarmonyPatches.MinAgeForAdulthood
PawnCacheRenderer.RenderPawn: PRE: AlienRace.HarmonyPatches.CacheRenderPawnPrefix
PawnCapacityUtility.CalculateLimbEfficiency: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnCapacityUtility.CalculateTagEfficiency: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnCapacityWorker_BloodFiltration.CalculateCapacityLevel: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnColumnWorker_Pregnant.GetIconFor: post: rjw.PawnColumnWorker_Patch_Icon.Postfix
PawnColumnWorker_Pregnant.GetTooltipText: PRE: rjw.PawnColumnWorker_Patch_Tooltip.Prefix
PawnGenerator.AddBlindness: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnGenerator.GenerateBodyType: post: AlienRace.HarmonyPatches.GenerateBodyTypePostfix
PawnGenerator.GenerateGearFor: post: AlienRace.HarmonyPatches.GenerateGearForPostfix
PawnGenerator.GenerateInitialHediffs: post: AlienRace.HarmonyPatches.GenerateInitialHediffsPostfix
PawnGenerator.GenerateNewPawnInternal: PRE: rjw.Patch_PawnGenerator.Generate_Nymph post: rjw.Patch_PawnGenerator.Fix_Nymph, rjw.Patch_PawnGenerator.Sexualize_GenerateNewPawnInternal, rjw.Patch_PawnGenerator.Fix_Newborn_styles
PawnGenerator.GeneratePawn: PRE: AlienRace.HarmonyPatches.GeneratePawnPrefix
PawnGenerator.GeneratePawnRelations: PRE: AlienRace.HarmonyPatches.GeneratePawnRelationsPrefix
PawnGenerator.GenerateRandomAge: PRE: AlienRace.HarmonyPatches.GenerateRandomAgePrefix
PawnGenerator.GenerateTraits: post: AlienRace.HarmonyPatches.GenerateTraitsPostfix TRANS: AlienRace.HarmonyPatches.GenerateTraitsTranspiler
PawnGenerator.TryGenerateNewPawnInternal: TRANS: AlienRace.HarmonyPatches.TryGenerateNewPawnTranspiler
PawnGraphicSet.ResolveAllGraphics: PRE: AlienRace.HarmonyPatches.ResolveAllGraphicsPrefix
PawnGraphicSet.ResolveApparelGraphics: PRE: RJW_Events.HarmonyPatch_StayNudeForOrgy.Prefix, Rimworld_Animations.HarmonyPatch_ResolveApparelGraphics.Prefix TRANS: rjwex.ResolveApparelGraphics_Patch.Transpiler
PawnKindDef.<ConfigErrors>d__99.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PawnRelationDef.GetGenderSpecificLabel: PRE: AlienRace.HarmonyPatches.GetGenderSpecificLabelPrefix
PawnRelationWorker_Child.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceChildPostfix
PawnRelationWorker_ExLover.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceExLoverPostfix
PawnRelationWorker_ExSpouse.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceExSpousePostfix
PawnRelationWorker_Fiance.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceFiancePostfix
PawnRelationWorker_Lover.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceLoverPostfix
PawnRelationWorker_Parent.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceParentPostfix
PawnRelationWorker_Sibling.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceSiblingPostfix
PawnRelationWorker_Spouse.GenerationChance: post: AlienRace.HarmonyPatches.GenerationChanceSpousePostfix
PawnRenderer.<DrawHeadHair>g__DrawApparel|39_0: TRANS: AlienRace.HarmonyPatches.DrawHeadHairApparelTranspiler
PawnRenderer.BaseHeadOffsetAt: post: AlienRace.HarmonyPatches.BaseHeadOffsetAtPostfix TRANS: AlienRace.HarmonyPatches.BaseHeadOffsetAtTranspiler
PawnRenderer.BodyAngle: TRANS: AlienRace.HarmonyPatches.PostureTranspiler
PawnRenderer.DrawHeadHair: PRE: Rimworld_Animations.HarmonyPatch_HeadHair.Prefix TRANS: AlienRace.HarmonyPatches.DrawHeadHairTranspiler
PawnRenderer.DrawPawnBody: TRANS: AlienRace.HarmonyPatches.DrawPawnBodyTranspiler
PawnRenderer.LayingFacing: TRANS: AlienRace.HarmonyPatches.PostureTranspiler
PawnRenderer.RenderPawnAt: TRANS: AlienRace.HarmonyPatches.PostureTranspiler, Rimworld_Animations.PawnRenderer_RenderPawnAt_Patch.Transpiler
PawnRenderer.RenderPawnInternal: PRE: rjwex.PawnRendererRenderInternal_Pathch.Prefix, Rimworld_Animations.HarmonyPatch_PawnRenderer.Prefix TRANS: AlienRace.HarmonyPatches.RenderPawnInternalTranspiler, Rimworld_Animations.HarmonyPatch_PawnRenderer.Transpiler
PawnStyleItemChooser.TotalStyleItemLikelihood: post: AlienRace.HarmonyPatches.TotalStyleItemLikelihoodPostfix
PawnStyleItemChooser.WantsToUseStyle: PRE: AlienRace.HarmonyPatches.WantsToUseStylePrefix post: AlienRace.HarmonyPatches.WantsToUseStylePostfix
PawnTextureAtlas..ctor: TRANS: AlienRace.HarmonyPatches.PawnTextureAtlasConstructorTranspiler
PawnTextureAtlas.<>c.<.ctor>b__12_0: TRANS: AlienRace.HarmonyPatches.PawnTextureAtlasConstructorFuncTranspiler
PawnTextureAtlas.TryGetFrameSet: TRANS: AlienRace.HarmonyPatches.PawnTextureAtlasGetFrameSetTranspiler
PawnUtility.FertileMateTarget: PRE: rjw.PATCH_PawnUtility_FertileMateTarget.Prefix post: rjw.PATCH_PawnUtility_FertileMateTarget.Postfix
PawnUtility.TrySpawnHatchedOrBornPawn: post: rjw.Patch_PawnUtility.Process_Child_HatchOrBirth
PawnWeaponGenerator.TryGenerateWeaponFor: PRE: AlienRace.HarmonyPatches.TryGenerateWeaponForPrefix post: AlienRace.HarmonyPatches.TryGenerateWeaponForPostfix
PawnWoundDrawer.<WriteCache>g__CalcAnchorData|16_3: post: AlienRace.HarmonyPatches.CalcAnchorDataPostfix
PawnWoundDrawer.<WriteCache>g__FindAnchors|16_1: post: AlienRace.HarmonyPatches.FindAnchorsPostfix
PawnWoundDrawer.RenderOverBody: PRE: AlienRace.HarmonyPatches.RenderOverBodyPrefix post: rjw.patch_semenOverlay.DrawSemen TRANS: AlienRace.HarmonyPatches.RenderOverBodyTranspiler
PawnWoundDrawer.WoundDebug: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_AgeTracker.BirthdayBiological: PRE: AlienRace.HarmonyPatches.BirthdayBiologicalPrefix
Pawn_AgeTracker.RecalculateLifeStageIndex: post: AlienRace.HarmonyPatches.RecalculateLifeStageIndexPostfix
Pawn_ApparelTracker.CanWearWithoutDroppingAnything: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_ApparelTracker.Notify_ApparelRemoved: post: rjw.PATCH_Pawn_ApparelTracker_Remove.on_remove
Pawn_ApparelTracker.TryDrop: PRE: rjw.PATCH_Pawn_ApparelTracker_TryDrop.prevent_locked_apparel_drop
Pawn_ApparelTracker.Wear: PRE: rjw.PATCH_Pawn_ApparelTracker_Wear.prevent_wear_by_gear post: rjw.PATCH_Pawn_ApparelTracker_Wear.on_wear TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_ApparelTracker.WouldReplaceLockedApparel: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_DrawTracker.get_DrawPos: PRE: Rimworld_Animations.HarmonyPatch_Pawn_DrawTracker.Prefix
Pawn_HealthTracker.CalculateMissingPartHediffsFromInjury: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_HealthTracker.CheckForStateChange: post: AlienRace.HarmonyPatches.CheckForStateChangePostfix
Pawn_HealthTracker.ShouldBeDead: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Pawn_MindState.SetupLastHumanMeatTick: PRE: AlienRace.HarmonyPatches.SetupLastHumanMeatTickPrefix
Pawn_RelationsTracker.CompatibilityWith: post: AlienRace.HarmonyPatches.CompatibilityWithPostfix
Pawn_RelationsTracker.SecondaryLovinChanceFactor: post: AlienRace.HarmonyPatches.SecondaryLovinChanceFactorPostfix TRANS: AlienRace.HarmonyPatches.SecondaryLovinChanceFactorTranspiler
Pawn_StoryTracker.get_SkinColor: post: AlienRace.HarmonyPatches.SkinColorPostfix
PlayDataLoader.DoPlayLoad: post: HugsLib.Patches.PlayDataLoader_Patch.InitModsHook
PlaySettings.DoPlaySettingsGlobalControls: post: rjw.RJW_corner_toggle.add_RJW_toggle
PreceptComp_Apparel_Desired.Notify_MemberGenerated: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
PreceptComp_KnowsMemoryThought.Notify_MemberWitnessedAction: TRANS: AlienRace.HarmonyPatches.KnowsMemoryThoughtTranspiler
PreceptComp_SelfTookMemoryThought.Notify_MemberTookAction: TRANS: AlienRace.HarmonyPatches.SelfTookMemoryThoughtTranspiler
PreceptComp_UnwillingToDo_Gendered.MemberWillingToDo: TRANS: AlienRace.HarmonyPatches.UnwillingWillingToDoGenderedTranspiler
RaceProperties.CanEverEat: post: AlienRace.HarmonyPatches.CanEverEatPostfix
Recipe_RemoveBodyPart.<GetPartsToApplyOn>d__2.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
RestUtility.CanUseBedEver: post: AlienRace.HarmonyPatches.CanUseBedEverPostfix
Room.UpdateRoomStatsAndRole: post: rjw.Building_Bed_Patch+Room_UpdateRoomStatsAndRole_Patch.Postfix
Root.OnGUI: post: HugsLib.Patches.Root_OnGUI_Patch.OnGUIHookUnfiltered
Root.Update: post: HugsLib.Patches.Root_Patch.UpdateHook
Root_Play.SetupForQuickTestPlay: TRANS: HugsLib.Patches.RootPlay_TestPlay_Patch.InjectCustomQuickstartSettings
Selector.Select: PRE: rjw.PawnSelect.Update_Designators_Permissions
SituationalThoughtHandler.TryCreateThought: PRE: AlienRace.HarmonyPatches.TryCreateThoughtPrefix
SkillRecord.CalculateTotallyDisabled: PRE: rjw.Patches_SkillRecordDebug.Prefix
StartingPawnUtility.NewGeneratedStartingPawn: TRANS: AlienRace.HarmonyPatches.NewGeneratedStartingPawnTranspiler
StatPart_BlindPsychicSensitivityOffset.ConsideredBlind: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
StatPart_NaturalNotMissingBodyPartsCoverage.<>c.<TryGetValue>b__2_0: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
StockGenerator_BuyExpensiveSimple.HandlesThingDef: post: rjw.PATCH_StockGenerator_BuyExpensiveSimple_HandlesThingDef.remove_RJW_stuff_fromtraderBUY
Thing.Ingested: PRE: AlienRace.HarmonyPatches.IngestedPrefix
Thing.SetFactionDirect: post: AlienRace.HarmonyPatches.SetFactionDirectPostfix
Thing.get_Rotation: PRE: Rimworld_Animations.HarmonyPatch_PawnRotation.Prefix
ThingDef.<ConfigErrors>d__314.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
ThoughtUtility.CanGetThought: post: AlienRace.HarmonyPatches.CanGetThoughtPostfix
ThoughtWorker_Man.CurrentSocialStateInternal: TRANS: AlienRace.HarmonyPatches.MisandryMisogynyTranspiler
ThoughtWorker_MissingTongue.CurrentStateInternal: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
ThoughtWorker_Woman.CurrentSocialStateInternal: TRANS: AlienRace.HarmonyPatches.MisandryMisogynyTranspiler
Toils_LayDown.ApplyBedThoughts: post: rjw.Building_Bed_Patch+Toils_LayDown_ApplyBedThoughts_Patch.Postfix
TradeUI.DrawTradeableRow: TRANS: AlienRace.HarmonyPatches.DrawTradeableRowTranspiler
Tradeable_Pawn.ResolveTrade: TRANS: AlienRace.HarmonyPatches.TradeablePawnResolveTranspiler
TraderCaravanUtility.GetTraderCaravanRole: TRANS: AlienRace.HarmonyPatches.GetTraderCaravanRoleTranspiler
TraitSet.GainTrait: PRE: AlienRace.HarmonyPatches.GainTraitPrefix
TransferableUIUtility.DoExtraAnimalIcons: post: rjw.TransferableUIUtility_Patch_Icon.Postfix
UIRoot.UIRootOnGUI: post: HugsLib.Patches.UIRoot_OnGUI_Patch.OnGUIHook
VerbProperties.<ConfigErrors>d__101.MoveNext: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
Verb_MeleeAttackDamage.DamageInfosToApply: post: AlienRace.HarmonyPatches.DamageInfosToApplyPostfix
VersionControl.DrawInfoInCorner: post: HarmonyMod.VersionControl_DrawInfoInCorner_Patch.Postfix
WITab_Caravan_Gear.TryEquipDraggedItem: PRE: rjw.PATCH_WITab_Caravan_Gear_TryEquipDraggedItem.prevent_locked_apparel_conflict TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
WITab_Caravan_Health.DoRow: TRANS: AlienRace.HarmonyPatches.BodyReferenceTranspiler
WorkGiver_GrowerHarvest.HasJobOnCell: post: AlienRace.HarmonyPatches.HasJobOnCellHarvestPostfix
WorkGiver_GrowerSow.ExtraRequirements: post: AlienRace.HarmonyPatches.ExtraRequirementsGrowerSowPostfix
WorkGiver_InteractAnimal.CanInteractWithAnimal: post: AlienRace.HarmonyPatches.CanInteractWithAnimalPostfix
WorkGiver_Researcher.ShouldSkip: post: AlienRace.HarmonyPatches.ShouldSkipResearchPostfix
WorkGiver_Sex.JobOnThing: PRE: Rimworld_Animations.HarmonyPatch_WorkGiverSex.Prefix
Harmony versions present: 2.2.0.0: net.pardeike.rimworld.lib.harmony, rimworld.erdelf.alien_race.main; 2.1.1.0: rimworldanim, rjw, rimworldevents; 2.1.0.0: UnlimitedHugs.HugsLib; 2.0.0.10: rimworld.ekss.rjwex

Platform information: (hidden, use publishing options to include)

Log file contents:
Mono path[0] = '[Rimworld_dir]/RimWorldWin64_Data/Managed'
Mono config path = '[Rimworld_dir]/MonoBleedingEdge/etc'
Initialize engine version: 2019.4.30f1 (e8c891080a1f)
[Subsystems] Discovering subsystems at path [Rimworld_dir]/RimWorldWin64_Data/UnitySubsystems
GfxDevice: [Renderer information redacted]
Begin MonoManager ReloadAssembly
RimWorld 1.3.3200 rev726
Mod Kurin Port Edition dependency (brrainz.harmony) needs to have <downloadUrl> and/or <steamWorkshopUrl> specified. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Mod Custom armor dependency (al9000.ceapparels) needs to have <downloadUrl> and/or <steamWorkshopUrl> specified. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

[HugsLib] version 9.0.1
[HugsLib][warn] Exception loading xml from C:/Users/Administrator/AppData/LocalLow/Ludeon Studios/RimWorld by Ludeon Studios\HugsLib\SpottedMods.xml. Loading defaults instead. Exception was: System.Xml.XmlException: Root element is missing.
  at System.Xml.XmlTextReaderImpl.Throw (System.Exception e) [0x00027] in <0f9699188f0c414ea6fb5557f5c16d15>:0 
  at System.Xml.XmlTextReaderImpl.ThrowWithoutLineInfo (System.String res) [0x00017] in <0f9699188f0c414ea6fb5557f5c16d15>:0 
  at System.Xml.XmlTextReaderImpl.ParseDocumentContent () [0x0035d] in <0f9699188f0c414ea6fb5557f5c16d15>:0 
  at System.Xml.XmlTextReaderImpl.Read () [0x0008c] in <0f9699188f0c414ea6fb5557f5c16d15>:0 
  at System.Xml.Linq.XDocument.Load (System.Xml.XmlReader reader, System.Xml.Linq.LoadOptions options) [0x00016] in <a9ef27d60e3144519c0741b6584ba229>:0 
  at System.Xml.Linq.XDocument.Load (System.String uri, System.Xml.Linq.LoadOptions options) [0x0000f] in <a9ef27d60e3144519c0741b6584ba229>:0 
  at System.Xml.Linq.XDocument.Load (System.String uri) [0x00000] in <a9ef27d60e3144519c0741b6584ba229>:0 
  at HugsLib.Core.PersistentDataManager.LoadData () [0x0001f] in <a56dbe2cf5184fe991f5fb736b3081b0>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

[HugsLib][warn] Skipping ModSpottingManager saving to preserve improperly loaded file data. Fix or delete the data file and try again. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Translation data for language Simplified Chinese has 9 errors. Generate translation report for more info. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Alien race successfully completed 180 patches with harmony.
[RJW] Humanoid Alien Races 2.0 is detected. Xenophile and Xenophobe traits active.
[RJWEx] [RJWEx] Patching...
[RJWEx] Gag graphics patch applied @ Verse.PawnGraphicSet.ResolveApparelGraphics as Transpiler
[RJWEx] ...done
[HugsLib] initializing RJW
Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNApparel_511TacTec_Ghost 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNApparel_PTABravoHelmet_Reaper 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.PawnKindDef named DRNTF_Colonist 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RN_MRE_USArmy 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.PawnKindDef named RH_Tactical_GermanShepherd 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to RimWorld.IncidentDef named MFI_Quest_PeaceTalks 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to RimWorld.IncidentDef named Quest_ItemStash 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

ScenPart has null incident after loading. Changing to Eclipse 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

ScenPart has null incident after loading. Changing to Eclipse 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Turret_Mk19MGLs 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named GFL_UMP9_Weapon 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named DRNTF_SummerHat 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Wall_SterileTeal 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named 404_HK416Beret 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named FateGrandOrder_Joanarmour 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Joy_PunchingBag 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Facility_IVDrip 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Kanade_NEGEVcostume 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNApparel_PTABravoHelmet_Reaper 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNGun_M16A4MilSpec 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Kanade_NEGEVcostume 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Turret_Mk19MGL 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named LU-IN 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Seat_SquareChair 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNGun_M27IAR_SD 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named WindPump 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named WaterTowerL 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNMedicine_MedicBag 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named AR_AR15costume 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Lighting_MURWallLightBlueVII 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNApparel_PTABravoHelmet_SpecOpsA 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named GasBoiler 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named KC-PrinZeugen 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNApparel_PTABravoHelmet_M50Gasmask 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Joy_InudstrialComputer 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Loaded file (Scenario) is from version 1.0.2282 rev726, we are running version 1.3.3200 rev726. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to RimWorld.FactionDef named DRNTF_Player 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Table_Royal3x3c 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named DRNTF_BionicTail 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named RNGun_RPD 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Could not load reference to Verse.ThingDef named Joy_Piano 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Some ScenParts had null defs. 
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Unloading 5 Unused Serialized files (Serialized files now loaded: 0)

Unloading 58 unused Assets to reduce memory usage. Loaded Objects now: 13272.
Total: 99.419400 ms (FindLiveObjects: 0.678000 ms CreateObjectMapping: 0.598400 ms MarkObjects: 97.986100 ms  DeleteObjects: 0.156500 ms)

Unloading 3 Unused Serialized files (Serialized files now loaded: 0)

Unloading 1 unused Assets to reduce memory usage. Loaded Objects now: 13564.
Total: 98.918900 ms (FindLiveObjects: 0.451400 ms CreateObjectMapping: 0.516300 ms MarkObjects: 97.867200 ms  DeleteObjects: 0.082900 ms)

Initializing new game with mods:
  - brrainz.harmony
  - Ludeon.RimWorld
  - UnlimitedHugs.HugsLib
  - erdelf.HumanoidAlienRaces
  - rim.job.world
  - rimworld.ekss.rjwex
  - c0ffee.rjw.events
  - c0ffee.rimworld.animations
  - Tory187.RJWAnimAddons.XtraAnims
[RJW]  母野山羊 default bodypart not found: Torso -skip.
[RJW]  母野山羊 default bodypart not found: Torso -skip.
[RJW]  母驼鹿 default bodypart not found: Torso -skip.
Unloading 0 Unused Serialized files (Serialized files now loaded: 0)

Unloading 0 unused Assets to reduce memory usage. Loaded Objects now: 17844.
Total: 141.915400 ms (FindLiveObjects: 0.632900 ms CreateObjectMapping: 0.894300 ms MarkObjects: 140.277500 ms  DeleteObjects: 0.110000 ms)

[RJW] rjwSextypeGet:dictionaryKey VaginalSex sextype Vaginal
JobDriver threw exception in initAction for pawn Tomboy driver=JobDriver_SexQuick (toilIndex=4) driver.job=(Quickie (Job_56) A=Thing_Human474)
System.TypeLoadException: Could not resolve type with token 0100001f (from typeref, class/assembly rjw.Modules.Interactions.Objects.InteractionWithExtension, RJW, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null)
  at Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_Start.RerollAnimations (Verse.Pawn pawn, System.Int32& AnimationTimeTicks, Verse.Thing bed, rjw.xxx+rjwSextype sexType, System.Boolean fastAnimForQuickie, rjw.SexProps sexProps) [0x00107] in <a7ae29b7e069487091993c5edf8d6c4d>:0 
  at Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_Start.Postfix (rjw.JobDriver_SexBaseInitiator& __instance) [0x000c1] in <a7ae29b7e069487091993c5edf8d6c4d>:0 
  at (wrapper dynamic-method) rjw.JobDriver_SexBaseInitiator.rjw.JobDriver_SexBaseInitiator.Start_Patch1(rjw.JobDriver_SexBaseInitiator)
  at rjw.JobDriver_SexQuick+<>c__DisplayClass1_0.<MakeNewToils>b__7 () [0x00030] in <a8724a76b26b4819a81be66641a8d240>:0 
  at Verse.AI.JobDriver.TryActuallyStartNextToil () [0x001de] in <cdbd0ed5089a418da09b9a259f9dbd8f>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

Curl error 42: Callback aborted
(Filename:  Line: 853)

[RJW] rjwSextypeGet:dictionaryKey Fisting sextype Fisting
JobDriver threw exception in initAction for pawn Tomboy driver=JobDriver_SexQuick (toilIndex=4) driver.job=(Quickie (Job_236) A=Thing_Human474)
System.TypeLoadException: Could not resolve type with token 0100001f (from typeref, class/assembly rjw.Modules.Interactions.Objects.InteractionWithExtension, RJW, Version=0.0.0.0, Culture=neutral, PublicKeyToken=null)
  at Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_Start.RerollAnimations (Verse.Pawn pawn, System.Int32& AnimationTimeTicks, Verse.Thing bed, rjw.xxx+rjwSextype sexType, System.Boolean fastAnimForQuickie, rjw.SexProps sexProps) [0x00107] in <a7ae29b7e069487091993c5edf8d6c4d>:0 
  at Rimworld_Animations.HarmonyPatch_JobDriver_SexBaseInitiator_Start.Postfix (rjw.JobDriver_SexBaseInitiator& __instance) [0x000c1] in <a7ae29b7e069487091993c5edf8d6c4d>:0 
  at (wrapper dynamic-method) rjw.JobDriver_SexBaseInitiator.rjw.JobDriver_SexBaseInitiator.Start_Patch1(rjw.JobDriver_SexBaseInitiator)
  at rjw.JobDriver_SexQuick+<>c__DisplayClass1_0.<MakeNewToils>b__7 () [0x00030] in <a8724a76b26b4819a81be66641a8d240>:0 
  at Verse.AI.JobDriver.TryActuallyStartNextToil () [0x001de] in <cdbd0ed5089a418da09b9a259f9dbd8f>:0  
(Filename: C:\buildslave\unity\build\Runtime/Export/Debug/Debug.bindings.h Line: 39)

