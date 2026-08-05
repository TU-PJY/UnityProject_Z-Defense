``` text
├── Prefabs
│   ├── ButtonAutoExecute
│   │   └── ButtonAutoExecute.cs
│   ├── Damageable
│   │   ├── BossZombie
│   │   │   ├── Behavior
│   │   │   │   ├── BossZombieEnum.cs
│   │   │   │   ├── CheckObstacleAction.cs
│   │   │   │   ├── NullCheckCondition.cs
│   │   │   │   ├── PlusIntAction.cs
│   │   │   │   ├── SearchTargetAction.cs
│   │   │   │   ├── StayAction.cs
│   │   │   │   ├── StayAndSetBoolInAnimOnEndAction.cs
│   │   │   │   └── StayAndSetIntOnEndAction.cs
│   │   │   ├── BossZombie.cs
│   │   │   └── BossZombieSpec.cs
│   │   ├── NormalZombie
│   │   │   ├── NormalZombie.cs
│   │   │   ├── NormalZombieAttackCollider.cs
│   │   │   └── NormalZombieSpec.cs
│   │   ├── Obstacle
│   │   │   ├── Editor
│   │   │   │   ├── ObstacleUpgradeCostCsvEditorTool.cs
│   │   │   │   └── ObstacleUpgradePopupUICreator.cs
│   │   │   ├── SO
│   │   │   │   └── Scripts
│   │   │   │       ├── ObstacleBuildEntrySO.cs
│   │   │   │       ├── ObstacleDefinitionSO.cs
│   │   │   │       ├── ObstaclePrefabProgressionSO.cs
│   │   │   │       ├── ObstacleSpec.cs
│   │   │   │       └── ObstacleUpgradeCostProfileSO.cs
│   │   │   ├── Obstacle.cs
│   │   │   ├── ObstacleBuildSlot.cs
│   │   │   ├── ObstaclePlacementController.cs
│   │   │   ├── ObstaclePlacementSlotUI.cs
│   │   │   ├── ObstaclePlacementUI.cs
│   │   │   ├── ObstacleUpgradePopupUI.cs
│   │   │   └── ObstacleUpgradeRuntimeController.cs
│   │   └── IDamageable.cs
│   ├── DropItemSystem
│   │   ├── DropItem.cs
│   │   ├── DropItemIndicator.cs
│   │   ├── DropItemParticle.cs
│   │   ├── ItemDropper.cs
│   │   └── ItemPickupParticle.cs
│   ├── ExitAskPannel
│   │   └── ExitAskPannel.cs
│   ├── HpUI
│   │   └── HpUI.cs
│   ├── InventorySystem
│   │   ├── Editor
│   │   │   └── InventorySystemEditor.cs
│   │   ├── InventorySystem.cs
│   │   ├── ItemMetaDataListSo.cs
│   │   ├── ItemMetaDataSo.cs
│   │   └── ItemSellBuyCostSo.cs
│   ├── InventoryUI
│   │   ├── InventoryUI.cs
│   │   └── PassEventToScrollRect.cs
│   ├── Survivor
│   │   ├── Editor
│   │   │   └── SurvivorInteractionUICreator.cs
│   │   ├── EngineerBuffTargetButton.cs
│   │   ├── EngineerBuffTargetPanelUI.cs
│   │   ├── Survivor.cs
│   │   ├── SurvivorInteractionController.cs
│   │   ├── SurvivorRescueSpawner.cs
│   │   ├── SurvivorRescueSpawnProfileSO.cs
│   │   ├── SurvivorRole.cs
│   │   └── SurvivorSpec.cs
│   ├── TitlePannel
│   │   └── TitlePannel.cs
│   ├── TransactionUI
│   │   └── TransactionUI.cs
│   ├── WorldUI
│   │   ├── WorldUIAnimation.cs
│   │   └── WorldUIHandler.cs
│   ├── ZombieDeathParticle
│   │   └── CoinParticleCreator.cs
│   └── ZombieSpawner
│       ├── ZombieSpawner.cs
│       ├── ZombieType.cs
│       └── ZombieWaveSpawnProfileSO.cs
├── Scenes
│   ├── KKW
│   │   └── Turret_Scene
│   │       ├── Editor
│   │       │   ├── TurretBalanceReportWindow.Calculation.cs
│   │       │   ├── TurretBalanceReportWindow.cs
│   │       │   ├── TurretBalanceReportWindow.Csv.cs
│   │       │   ├── TurretBalanceReportWindow.CurrencyProjection.cs
│   │       │   ├── TurretBalanceReportWindow.Graph.cs
│   │       │   ├── TurretBalanceReportWindow.Input.cs
│   │       │   ├── TurretBalanceReportWindow.Obstacle.Calculation.cs
│   │       │   ├── TurretBalanceReportWindow.Obstacle.Table.cs
│   │       │   ├── TurretBalanceReportWindow.Table.cs
│   │       │   ├── TurretBalanceReportWindow.TableModel.cs
│   │       │   ├── TurretBalanceReportWindow.Types.cs
│   │       │   ├── TurretDataCsvEditorTool.cs
│   │       │   ├── TurretEconomySimulationCalculator.cs
│   │       │   ├── TurretEconomyValidator.cs
│   │       │   ├── TurretEvolutionCostCsvEditorTool.cs
│   │       │   ├── TurretEvolutionGraphBuilder.cs
│   │       │   ├── TurretSpecialAbilityDpsCalculator.cs
│   │       │   ├── TurretSpeciesDetailCalculator.cs
│   │       │   ├── TurretWaveClearRankingCalculator.cs
│   │       │   ├── TurretWaveRuntimeAnalyzer.cs
│   │       │   └── ZombieRewardExpectationCalculator.cs
│   │       └── Scripts
│   │           ├── Placement
│   │           │   ├── TurretBaseSlot.cs
│   │           │   ├── TurretPlacementController.cs
│   │           │   ├── TurretPlacementPreview.cs
│   │           │   ├── TurretPlacementSlotUI.cs
│   │           │   ├── TurretPlacementUI.cs
│   │           │   ├── TurretSelectionLayerUtility.cs
│   │           │   └── TurretShopEntrySO.cs
│   │           ├── UI
│   │           │   ├── DamageMeter
│   │           │   │   ├── TurretDamageMeterColorProfileSO.cs
│   │           │   │   ├── TurretDamageMeterManager.cs
│   │           │   │   ├── TurretDamageMeterRowUI.cs
│   │           │   │   ├── TurretDamageMeterSource.cs
│   │           │   │   └── TurretDamageMeterUI.cs
│   │           │   ├── TechTree
│   │           │   │   ├── TurretTechTreeDetailPopupUI.cs
│   │           │   │   ├── TurretTechTreeLineUI.cs
│   │           │   │   ├── TurretTechTreeNodeState.cs
│   │           │   │   ├── TurretTechTreeNodeUI.cs
│   │           │   │   ├── TurretTechTreeOpenButton.cs
│   │           │   │   ├── TurretTechTreeUIController.cs
│   │           │   │   ├── TurretTechTreeViewProfileSO.cs
│   │           │   │   └── TurretTechTreeZoomController.cs
│   │           │   ├── TurretCurrencyDisplayUtility.cs
│   │           │   ├── TurretDetailPopupUI.cs
│   │           │   ├── TurretEvolutionCandidatePressForwarder.cs
│   │           │   ├── TurretEvolutionPopupUI.cs
│   │           │   ├── TurretFeedbackPopupSettings.cs
│   │           │   ├── TurretInfoPopupUI.cs
│   │           │   ├── TurretItemDescriptionOpenButton.cs
│   │           │   ├── TurretItemDescriptionPopupUI.cs
│   │           │   ├── TurretItemDescriptionRelationSlotUI.cs
│   │           │   ├── TurretPopupPageUI.cs
│   │           │   ├── TurretSelectionContext.cs
│   │           │   ├── TurretSelectionUIController.cs
│   │           │   ├── TurretSelectPopupUI.cs
│   │           │   ├── TurretSkillPopupUI.cs
│   │           │   └── TurretUpgradePopupUI.cs
│   │           ├── BeamAttackProfileSO.cs
│   │           ├── BeamFiringEvent.cs
│   │           ├── DetachedPooledChildReturner.cs
│   │           ├── ElectroChainCoreLineEffect.cs
│   │           ├── ElectroChainLightningUtility.cs
│   │           ├── ElectroChainLinkAnchorTracker.cs
│   │           ├── ElectroChainLinkEffectUtility.cs
│   │           ├── ElectroStatusProfileSO.cs
│   │           ├── ElectroTurretStatGrowthProfileSO.cs
│   │           ├── EnemyPatrolMover.cs
│   │           ├── FrostFreezeExplosionDamageTimer.cs
│   │           ├── FrostStatusEffectUtility.cs
│   │           ├── FrostStatusProfileSO.cs
│   │           ├── HovlProjectileHitEffectUtility.cs
│   │           ├── HovlProjectilePierceGuard.cs
│   │           ├── IElectroStatusEffectReceiver.cs
│   │           ├── IFrostStatusEffectReceiver.cs
│   │           ├── IgnitionConeDetector.cs
│   │           ├── IgnitionDamageApplier.cs
│   │           ├── IgnitionStatusProfileSO.cs
│   │           ├── IgnitionTurretStatGrowthProfileSO.cs
│   │           ├── IIgnitionStatusEffectReceiver.cs
│   │           ├── IPoisonStatusEffectReceiver.cs
│   │           ├── ITurretRuntimeStatReceiver.cs
│   │           ├── ITurretStatusProfileReceiver.cs
│   │           ├── LevelHoldButton.cs
│   │           ├── PoisonDeathBurstEffectUtility.cs
│   │           ├── PoisonDeathBurstProfileSO.cs
│   │           ├── PoisonStatusProfileSO.cs
│   │           ├── PoisonStatusRuntimeUtility.cs
│   │           ├── PoisonTurretStatGrowthProfileSO.cs
│   │           ├── PooledEffectReturner.cs
│   │           ├── PooledProjectileReturner.cs
│   │           ├── ProjectileBoundary.cs
│   │           ├── ProjectileComponentCache.cs
│   │           ├── ProjectileDamageDealer.cs
│   │           ├── ProjectileHitDetector.cs
│   │           ├── TestDamageableTarget.cs
│   │           ├── TurretAimPointUtility.cs
│   │           ├── TurretDamagePolishProfileSO.cs
│   │           ├── TurretDamagePolishResult.cs
│   │           ├── TurretDefinitionRuntimeController.cs
│   │           ├── TurretDefinitionSO.cs
│   │           ├── TurretEconomyLogUtility.cs
│   │           ├── TurretEngineerBuffReceiver.cs
│   │           ├── TurretEvolutionProgressionSO.cs
│   │           ├── TurretEvolutionRuntimeUI.cs
│   │           ├── TurretLeadPredictionUtility.cs
│   │           ├── TurretProjectileScaleProgressionSO.cs
│   │           ├── TurretRangeIndicator.cs
│   │           ├── TurretRankBand.cs
│   │           ├── TurretRankBillboard.cs
│   │           ├── TurretRankDisplayController.cs
│   │           ├── TurretRankDisplayProfileSO.cs
│   │           ├── TurretRuntimeStat.cs
│   │           ├── TurretStatCalculator.cs
│   │           ├── TurretStatGrowthProfileSO.cs
│   │           ├── TurretStatProfileApplier.cs
│   │           ├── TurretStatProfileSO.cs
│   │           ├── TurretUpgradeCostProfileSO.cs
│   │           ├── TurretVFXProfileSO.cs
│   │           └── TurretVFXProgressionSO.cs
│   └── PJY
│       ├── CubeSpawnTest.cs
│       ├── EventSystemDebugger.cs
│       └── ItemDropTest.cs
├── Scripts
│   ├── Audio
│   │   ├── AudioCueSO.cs
│   │   ├── ITurretAudioEventPlayer.cs
│   │   ├── PooledAudioSource.cs
│   │   ├── ProjectAudioBus.cs
│   │   ├── ProjectAudioFeelBridge.cs
│   │   ├── ProjectAudioHandle.cs
│   │   ├── ProjectAudioManager.cs
│   │   ├── ProjectAudioPlaybackMode.cs
│   │   ├── ProjectAudioVolumeSlider.cs
│   │   ├── ProjectAudioVolumeTarget.cs
│   │   ├── ProjectBgmPlayer.cs
│   │   ├── TurretAudioController.cs
│   │   ├── TurretAudioEvent.cs
│   │   ├── TurretAudioFireEventRelay.cs
│   │   ├── TurretAudioProfileSO.cs
│   │   └── UIButtonAudioFeedback.cs
│   ├── CameraTools
│   │   ├── CameraController.cs
│   │   └── CameraTouchHandler.cs
│   ├── Editor
│   │   ├── ItemDataEditorTool.cs
│   │   ├── RewardCurrencyTypeDrawer.cs
│   │   └── ZombieBalanceCsvEditorTool.cs
│   ├── Rewards
│   │   ├── BillboardUtil.cs
│   │   ├── ResourceCost.cs
│   │   ├── RewardCurrencyType.cs
│   │   ├── RewardEntry.cs
│   │   ├── RewardGrantUtility.cs
│   │   ├── RewardResult.cs
│   │   ├── ZombieRewardContext.cs
│   │   ├── ZombieRewardModifier.cs
│   │   ├── ZombieRewardProfileSO.cs
│   │   ├── ZombieRewardSituation.cs
│   │   ├── ZombieWaveDpsMeasurementProfileSO.cs
│   │   └── ZombieWaveDpsRuntimeRecorder.cs
│   ├── SellerTruck
│   │   └── SellerTruckMovement.cs
│   ├── Singleton
│   │   ├── DisplayManager
│   │   │   └── DisplayManager.cs
│   │   ├── DropItemManager
│   │   │   └── DropItemManager.cs
│   │   ├── FeelManager
│   │   │   └── FeelManager.cs
│   │   ├── GameManager
│   │   │   └── GameManager.cs
│   │   ├── MemoryPool
│   │   │   ├── MemoryPool.cs
│   │   │   └── MemoryPoolPrewarmer.cs
│   │   ├── SaveManager
│   │   │   ├── ISaveable.cs
│   │   │   └── SaveManager.cs
│   │   └── UISoundPlayer
│   │       └── UISoundPlayer.cs
│   ├── StatusEffects
│   │   ├── Editor
│   │   │   └── StatusEffectVisualSlotDrawer.cs
│   │   ├── ElectroShockStackVisualFader.cs
│   │   ├── ElectroShockStackVisualModeController.cs
│   │   ├── ElectroStatusRuntime.cs
│   │   ├── FrostStatusRuntime.cs
│   │   ├── IgnitionStatusRuntime.cs
│   │   ├── PoisonStatusRuntime.cs
│   │   ├── StatusEffectVisualAlphaFader.cs
│   │   └── StatusEffectVisualController.cs
│   ├── Targeting
│   │   ├── ElectroShockTargetCandidateFilter.cs
│   │   ├── FrostFreezeSuppressedTargetCandidateFilter.cs
│   │   ├── IAimPointProvider.cs
│   │   ├── IgnitionBurningTargetCandidateFilter.cs
│   │   ├── ITargetCandidateFilter.cs
│   │   ├── PoisonLethalTargetCandidateFilter.cs
│   │   └── StickyCurrentTargetRetentionFilter.cs
│   ├── UI
│   │   ├── DropItemGetLog
│   │   │   ├── DropItemGetLog.cs
│   │   │   └── DropItemGetLogText.cs
│   │   ├── Editor
│   │   │   └── GameOverPanelUICreator.cs
│   │   ├── ItemUI
│   │   │   └── ItemIndicator.cs
│   │   ├── MenuUI
│   │   │   ├── MainMenuButton.cs
│   │   │   └── MainMenuUI.cs
│   │   ├── PowerSavingButton
│   │   │   └── PowerSavingButton.cs
│   │   ├── PowerSavingSwitcher
│   │   │   └── PowerSavingSwitcher.cs
│   │   ├── TimeScaleButton
│   │   │   └── TimeScaleButton.cs
│   │   ├── TransactionUI
│   │   │   └── TransactionPopup.cs
│   │   ├── WaveUI
│   │   │   ├── WaveIndicator.cs
│   │   │   └── WavePopup.cs
│   │   ├── WorldUI
│   │   │   └── WorldButton.cs
│   │   ├── BillboardCanvas.cs
│   │   ├── GameOverPanelUI.cs
│   │   ├── TouchBackHandler.cs
│   │   ├── UIAnimationValues.cs
│   │   ├── UIManager.cs
│   │   ├── WarningPopup.cs
│   │   └── WarningPopupManager.cs
│   ├── DamageInfo.cs
│   ├── DamagePopupPolicy.cs
│   ├── DamagePopupPolicyProfileSO.cs
│   ├── DamagePopupPolicyResolver.cs
│   ├── DamagePopupSettings.cs
│   ├── DamagePopupSpawner.cs
│   ├── DamagePopupTargetType.cs
│   ├── DamagePopupType.cs
│   ├── DisableAfterSeconds.cs
│   ├── DnpDamagePopupBackend.cs
│   └── IDamagePopupRenderBackend.cs
├── PROJECT_README.cs
├── REWARD_CURRENCY_SYSTEM_PLAN.cs
├── STATUS_EFFECT_SYSTEM_README.cs
├── TeamCodingConvention.cs
├── TURRET_DATA_STRUCTURE_PLAN.cs
└── TURRET_UI_REWORK_PLAN.cs
```
