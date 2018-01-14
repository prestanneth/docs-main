Client is a class exported to Perl that represent the Client object from EQEmu. All Client are also [Mob](Perl-Mob).

### Properties
```
client.null -- Returns true if this object is null
client.valid -- Returns true if this object is not null
```

### Member Functions
* [$client->AccountID() # uint](Perl-Client-AccountID)
* [$client->AccountName() # string](Perl-Client-AccountName)
* [$client->AddAAPoints(number) # void](Perl-Client-AddAAPoints)
* [$client->AddAlternateCurrencyValue(uint32 currency_id, int32 amount) # void](Perl-Client-AddAlternateCurrencyValue)
* [$client->AddCrystals(RadiantCount, EbonCount) # void](Perl-Client-AddCrystals)
* [$client->AddEXP(add_exp, conlevel) # void](Perl-Client-AddEXP)
* [$client->AddLevelBasedExp(exp_percentage, int max_level) # void](Perl-Client-AddLevelBasedExp)
* [$client->AddMoneyToPP(int copper, int silver, int gold, int platinum, updateclient) # void](Perl-Client-AddMoneyToPP)
* [$client->AddPVPPoints(Points) # void](Perl-Client-AddPVPPoints)
* [$client->AddSkill(skillid, int value) # void](Perl-Client-AddSkill)
* [$client->Admin() # int](Perl-Client-Admin)
* [$client->AssignTask(TaskID, NPCID, bool enforce_level_requirement) # void](Perl-Client-AssignTask)
* [$client->AssignToInstance(int instance_id) # void](Perl-Client-AssignToInstance)
* [$client->AutoSplitEnabled() # bool](Perl-Client-AutoSplitEnabled)
* [$client->BreakInvis() # void](Perl-Client-BreakInvis)
* [$client->CalcPriceMod(other) # double](Perl-Client-CalcPriceMod)
* [$client->CanHaveSkill(skill_id) # bool](Perl-Client-CanHaveSkill)
* [$client->ChangeLastName(string in_lastname) # void](Perl-Client-ChangeLastName)
* [$client->CharacterID() # uint](Perl-Client-CharacterID)
* [$client->CheckIncreaseSkill(skillid, chancemodi) # bool](Perl-Client-CheckIncreaseSkill)
* [$client->CheckSpecializeIncrease(int spell_id) # void](Perl-Client-CheckSpecializeIncrease)
* [$client->ClearCompassMark() # void](Perl-Client-ClearCompassMark)
* [$client->ClearZoneFlag(int zone_id) # void](Perl-Client-ClearZoneFlag)
* [$client->Connected() # bool](Perl-Client-Connected)
* [$client->DecreaseByID(int type, amt) # bool](Perl-Client-DecreaseByID)
* [$client->DeleteItemInInventory(slot_id, int quantity) # void](Perl-Client-DeleteItemInInventory)
* [$client->Disconnect() # void](Perl-Client-Disconnect)
* [$client->DropItem(slot_id) # void](Perl-Client-DropItem)
* [$client->Duck() # void](Perl-Client-Duck)
* [$client->Escape() # void](Perl-Client-Escape)
* [$client->ExpeditionMessage(ExpdID, Message) # void](Perl-Client-ExpeditionMessage)
* [$client->FailTask(TaskID) # void](Perl-Client-FailTask)
* [$client->ForageItem() # void](Perl-Client-ForageItem)
* [$client->GetAAExp() # uint](Perl-Client-GetAAExp)
* [$client->GetAALevel(aaskillid) # uint](Perl-Client-GetAALevel)
* [$client->GetAAPercent() # uint](Perl-Client-GetAAPercent)
* [$client->GetAAPoints() # uint](Perl-Client-GetAAPoints)
* [$client->GetAccountFlag(flag) # string](Perl-Client-GetAccountFlag)
* [$client->GetAggroCount() # int](Perl-Client-GetAggroCount)
* [$client->GetAllMoney() # int](Perl-Client-GetAllMoney)
* [$client->GetAnon() # uint](Perl-Client-GetAnon)
* [$client->GetAugmentAt(int slot, aug_slot) # void](Perl-Client-GetAugmentAt)
* [$client->GetAugmentIDAt(slot_id, augslot) # int](Perl-Client-GetAugmentIDAt)
* [$client->GetBaseAGI() # uint](Perl-Client-GetBaseAGI)
* [$client->GetBaseCHA() # uint](Perl-Client-GetBaseCHA)
* [$client->GetBaseDEX() # uint](Perl-Client-GetBaseDEX)
* [$client->GetBaseFace() # uint](Perl-Client-GetBaseFace)
* [$client->GetBaseINT() # uint](Perl-Client-GetBaseINT)
* [$client->GetBaseSTA() # uint](Perl-Client-GetBaseSTA)
* [$client->GetBaseSTR() # uint](Perl-Client-GetBaseSTR)
* [$client->GetBaseWIS() # uint](Perl-Client-GetBaseWIS)
* [$client->GetBecomeNPCLevel() # uint](Perl-Client-GetBecomeNPCLevel)
* [$client->GetBindHeading(index) # double](Perl-Client-GetBindHeading)
* [$client->GetBindX(index) # double](Perl-Client-GetBindX)
* [$client->GetBindY(index) # double](Perl-Client-GetBindY)
* [$client->GetBindZ(index) # double](Perl-Client-GetBindZ)
* [$client->GetBindZoneID(index) # uint](Perl-Client-GetBindZoneID)
* [$client->GetCarriedMoney() # int](Perl-Client-GetCarriedMoney)
* [$client->GetCharacterFactionLevel(faction_id) # int](Perl-Client-GetCharacterFactionLevel)
* [$client->GetClientVersion() # uint](Perl-Client-GetClientVersion)
* [$client->GetClientVersionBit() # uint](Perl-Client-GetClientVersionBit)
* [$client->GetCorpseCount() # int](Perl-Client-GetCorpseCount)
* [$client->GetCorpseID(corpse) # int](Perl-Client-GetCorpseID)
* [$client->GetCorpseItemAt(corpse_id, slotid) # int](Perl-Client-GetCorpseItemAt)
* [$client->GetCustomItemData(slot_id, identifier) # string](Perl-Client-GetCustomItemData)
* [$client->GetDiscSlotBySpellID(int spell_id) # int](Perl-Client-GetDiscSlotBySpellID)
* [$client->GetDuelTarget() # uint](Perl-Client-GetDuelTarget)
* [$client->GetEbonCrystals() # uint](Perl-Client-GetEbonCrystals)
* [$client->GetEndurance() # uint](Perl-Client-GetEndurance)
* [$client->GetEnduranceRatio() # uint](Perl-Client-GetEnduranceRatio)
* [$client->GetEXP() # uint](Perl-Client-GetEXP)
* [$client->GetFace() # uint](Perl-Client-GetFace)
* [$client->GetFactionLevel(int char_id, int npc_id, p_race, p_class, p_deity, pFaction, tnpc) # int](Perl-Client-GetFactionLevel)
* [$client->GetFeigned() # bool](Perl-Client-GetFeigned)
* [$client->GetFreeSpellBookSlot(start_slot) # int](Perl-Client-GetFreeSpellBookSlot)
* [$client->GetGM() # bool](Perl-Client-GetGM)
* [$client->GetGroup() # void](Perl-Client-GetGroup)
* [$client->GetGroupPoints() # uint](Perl-Client-GetGroupPoints)
* [$client->GetHorseId() # uint](Perl-Client-GetHorseId)
* [$client->GetHunger() # int](Perl-Client-GetHunger)
* [$client->GetInstanceID() # uint](Perl-Client-GetInstanceID)
* [$client->GetInstrumentMod(int spell_id) # uint](Perl-Client-GetInstrumentMod)
* [$client->GetIP() # uint](Perl-Client-GetIP)
* [$client->GetItemAt(int slot) # void](Perl-Client-GetItemAt)
* [$client->GetItemIDAt(slot_id) # int](Perl-Client-GetItemIDAt)
* [$client->GetItemInInventory(slot_id) # void](Perl-Client-GetItemInInventory)
* [$client->GetLanguageSkill(n) # uint](Perl-Client-GetLanguageSkill)
* [$client->GetLastName() # string](Perl-Client-GetLastName)
* [$client->GetLDoNLosses() # uint](Perl-Client-GetLDoNLosses)
* [$client->GetLDoNLossesTheme(theme) # uint](Perl-Client-GetLDoNLossesTheme)
* [$client->GetLDoNPointsTheme(theme) # uint](Perl-Client-GetLDoNPointsTheme)
* [$client->GetLDoNWins() # uint](Perl-Client-GetLDoNWins)
* [$client->GetLDoNWinsTheme(theme) # uint](Perl-Client-GetLDoNWinsTheme)
* [$client->GetMaxEndurance() # uint](Perl-Client-GetMaxEndurance)
* [$client->GetModCharacterFactionLevel(faction_id) # int](Perl-Client-GetModCharacterFactionLevel)
* [$client->GetPVP() # bool](Perl-Client-GetPVP)
* [$client->GetPVPPoints() # uint](Perl-Client-GetPVPPoints)
* [$client->GetRadiantCrystals() # uint](Perl-Client-GetRadiantCrystals)
* [$client->GetRaid() # void](Perl-Client-GetRaid)
* [$client->GetRaidPoints() # uint](Perl-Client-GetRaidPoints)
* [$client->GetRawItemAC() # int](Perl-Client-GetRawItemAC)
* [$client->GetRawSkill(skill_id) # uint](Perl-Client-GetRawSkill)
* [$client->GetSkill(skill_id) # uint](Perl-Client-GetSkill)
* [$client->GetSkillPoints() # uint](Perl-Client-GetSkillPoints)
* [$client->GetSpellBookSlotBySpellID(int spell_id) # int](Perl-Client-GetSpellBookSlotBySpellID)
* [$client->GetSpentAA() # uint](Perl-Client-GetSpentAA)
* [$client->GetStartZone() # uint](Perl-Client-GetStartZone)
* [$client->GetTargetRingX() # double](Perl-Client-GetTargetRingX)
* [$client->GetTargetRingY() # double](Perl-Client-GetTargetRingY)
* [$client->GetTargetRingZ() # double](Perl-Client-GetTargetRingZ)
* [$client->GetTaskActivityDoneCount(TaskID, ActivityID) # int](Perl-Client-GetTaskActivityDoneCount)
* [$client->GetThirst() # int](Perl-Client-GetThirst)
* [$client->GetTotalSecondsPlayed() # uint](Perl-Client-GetTotalSecondsPlayed)
* [$client->GetWeight() # uint](Perl-Client-GetWeight)
* [$client->GMKill() # void](Perl-Client-GMKill)
* [$client->GoFish() # void](Perl-Client-GoFish)
* [$client->GrantAlternateAdvancementAbility(aa_id, points, ignore_cost) # bool](Perl-Client-GrantAlternateAdvancementAbility)
* [$client->GuildID() # uint](Perl-Client-GuildID)
* [$client->GuildRank() # uint](Perl-Client-GuildRank)
* [$client->HasSkill(skill_id) # bool](Perl-Client-HasSkill)
* [$client->HasSpellScribed(int spell_id) # bool](Perl-Client-HasSpellScribed)
* [$client->HasZoneFlag(int zone_id) # bool](Perl-Client-HasZoneFlag)
* [$client->Hungry() # bool](Perl-Client-Hungry)
* [$client->IncreaseLanguageSkill(skill_id, int value) # void](Perl-Client-IncreaseLanguageSkill)
* [$client->IncreaseSkill(skill_id, int value) # void](Perl-Client-IncreaseSkill)
* [$client->IncrementAA(aaskillid) # void](Perl-Client-IncrementAA)
* [$client->IncStats(int type, increase_val) # void](Perl-Client-IncStats)
* [$client->InZone() # bool](Perl-Client-InZone)
* [$client->IsBecomeNPC() # bool](Perl-Client-IsBecomeNPC)
* [$client->IsDueling() # bool](Perl-Client-IsDueling)
* [$client->IsGrouped() # bool](Perl-Client-IsGrouped)
* [$client->IsLD() # bool](Perl-Client-IsLD)
* [$client->IsMedding() # bool](Perl-Client-IsMedding)
* [$client->IsRaidGrouped() # bool](Perl-Client-IsRaidGrouped)
* [$client->IsSitting() # bool](Perl-Client-IsSitting)
* [$client->IsTaskActive(TaskID) # bool](Perl-Client-IsTaskActive)
* [$client->IsTaskActivityActive(TaskID, ActivityID) # bool](Perl-Client-IsTaskActivityActive)
* [$client->IsTaskCompleted(TaskID) # bool](Perl-Client-IsTaskCompleted)
* [$client->KeyRingAdd(int item_id) # void](Perl-Client-KeyRingAdd)
* [$client->KeyRingCheck(int item_id) # bool](Perl-Client-KeyRingCheck)
* [$client->Kick() # void](Perl-Client-Kick)
* [$client->LearnRecipe(recipe_id) # void](Perl-Client-LearnRecipe)
* [$client->LeaveGroup() # void](Perl-Client-LeaveGroup)
* [$client->LoadZoneFlags() # void](Perl-Client-LoadZoneFlags)
* [$client->MarkCompassLoc(float x, float y, float z) # void](Perl-Client-MarkCompassLoc)
* [$client->MaxSkill(skillid, class, int level) # uint](Perl-Client-MaxSkill)
* [$client->MemSpell(int spell_id, int slot, update_client) # void](Perl-Client-MemSpell)
* [$client->MovePC(zoneID, float x, float y, float z, float heading) # void](Perl-Client-MovePC)
* [$client->MovePCInstance(zoneID, instanceID, float x, float y, float z, float heading) # void](Perl-Client-MovePCInstance)
* [$client->NPCSpawn(target_npc, option, respawntime) # void](Perl-Client-NPCSpawn)
* [$client->NukeItem(itemnum, where_to_check) # uint](Perl-Client-NukeItem)
* [$client->OpenLFGuildWindow() # void](Perl-Client-OpenLFGuildWindow)
* [$client->PlayMP3(fname) # void](Perl-Client-PlayMP3)
* [$client->QuestReward(mob, int copper, int silver, int gold, int platinum, itemid, exp, faction) # void](Perl-Client-QuestReward)
* [$client->ReadBook(Book Text, Type) # void](Perl-Client-ReadBook)
* [$client->RefundAA() # void](Perl-Client-RefundAA)
* [$client->RemoveFromInstance(int instance_id) # void](Perl-Client-RemoveFromInstance)
* [$client->RemoveNoRent() # void](Perl-Client-RemoveNoRent)
* [$client->ResetAA() # void](Perl-Client-ResetAA)
* [$client->ResetTrade() # void](Perl-Client-ResetTrade)
* [$client->Save(iCommitNow) # bool](Perl-Client-Save)
* [$client->SaveBackup() # void](Perl-Client-SaveBackup)
* [$client->ScribeSpell(int spell_id, int slot, update_client) # void](Perl-Client-ScribeSpell)
* [$client->SendColoredText(int color, string message) # void](Perl-Client-SendColoredText)
* [$client->SendMarqueeMessage(int type, int priority, int fade_in, int fade_out, int duration, msg) # void](Perl-Client-SendMarqueeMessage)
* [$client->SendOPTranslocateConfirm(Caster, SpellID) # void](Perl-Client-SendOPTranslocateConfirm)
* [$client->SendSound() # void](Perl-Client-SendSound)
* [$client->SendTargetCommand(in_entid) # void](Perl-Client-SendTargetCommand)
* [$client->SendWebLink(website) # void](Perl-Client-SendWebLink)
* [$client->SendZoneFlagInfo(to) # void](Perl-Client-SendZoneFlagInfo)
* [$client->SetAAPoints(points) # void](Perl-Client-SetAAPoints)
* [$client->SetAATitle(txt, save) # void](Perl-Client-SetAATitle)
* [$client->SetAccountFlag(flag, int value) # void](Perl-Client-SetAccountFlag)
* [$client->SetBaseClass(i) # void](Perl-Client-SetBaseClass)
* [$client->SetBaseGender(i) # void](Perl-Client-SetBaseGender)
* [$client->SetBaseRace(i) # void](Perl-Client-SetBaseRace)
* [$client->SetBecomeNPC(flag) # void](Perl-Client-SetBecomeNPC)
* [$client->SetBecomeNPCLevel(int level) # void](Perl-Client-SetBecomeNPCLevel)
* [$client->SetBindPoint(to_zone) # void](Perl-Client-SetBindPoint)
* [$client->SetCustomItemData(slot_id, identifier, int value) # void](Perl-Client-SetCustomItemData)
* [$client->SetDeity(i) # void](Perl-Client-SetDeity)
* [$client->SetDueling(duel) # void](Perl-Client-SetDueling)
* [$client->SetDuelTarget(set_id) # void](Perl-Client-SetDuelTarget)
* [$client->SetEndurance(Endurance) # void](Perl-Client-SetEndurance)
* [$client->SetEXP(set_exp, set_aaxp, resexp) # void](Perl-Client-SetEXP)
* [$client->SetFactionLevel(int char_id, int npc_id, char_class, char_race, char_deity) # void](Perl-Client-SetFactionLevel)
* [$client->SetFactionLevel2(int char_id, faction_id, char_class, char_race, char_deity, int value, int temp) # void](Perl-Client-SetFactionLevel2)
* [$client->SetFeigned(in_feigned) # void](Perl-Client-SetFeigned)
* [$client->SetGM(toggle) # void](Perl-Client-SetGM)
* [$client->SetHorseId(horseid_in) # void](Perl-Client-SetHorseId)
* [$client->SetHunger(in_hunger) # void](Perl-Client-SetHunger)
* [$client->SetHunger(in_hunger, in_thirst) # void](Perl-Client-SetHunger)
* [$client->SetLanguageSkill(langid, int value) # void](Perl-Client-SetLanguageSkill)
* [$client->SetMaterial(slot_id, int item_id) # void](Perl-Client-SetMaterial)
* [$client->SetPVP(toggle) # void](Perl-Client-SetPVP)
* [$client->SetSkill(skill_num, int value) # void](Perl-Client-SetSkill)
* [$client->SetSkillPoints(inp) # void](Perl-Client-SetSkillPoints)
* [$client->SetStartZone(zoneid , float x, float y, float z) # void](Perl-Client-SetStartZone)
* [$client->SetStats(int type, increase_val) # void](Perl-Client-SetStats)
* [$client->SetThirst(in_thirst) # void](Perl-Client-SetThirst)
* [$client->SetTint(slot_id, int color) # void](Perl-Client-SetTint)
* [$client->SetTitleSuffix(txt, save) # void](Perl-Client-SetTitleSuffix)
* [$client->SetZoneFlag(int zone_id) # void](Perl-Client-SetZoneFlag)
* [$client->SignalClient(data) # void](Perl-Client-SignalClient)
* [$client->SilentMessage(Message) # void](Perl-Client-SilentMessage)
* [$client->SlotConvert2(int slot) # uint](Perl-Client-SlotConvert2)
* [$client->Stand() # void](Perl-Client-Stand)
* [$client->SummonItem(int item_id, int charges) # void](Perl-Client-SummonItem)
* [$client->TakeMoneyFromPP(int copper, updateclient) # bool](Perl-Client-TakeMoneyFromPP)
* [$client->TGB() # bool](Perl-Client-TGB)
* [$client->Thirsty() # bool](Perl-Client-Thirsty)
* [$client->TrainDiscBySpellID(int spell_id) # void](Perl-Client-TrainDiscBySpellID)
* [$client->Undye() # void](Perl-Client-Undye)
* [$client->UnmemSpell(int slot, update_client) # void](Perl-Client-UnmemSpell)
* [$client->UnmemSpellAll(update_client) # void](Perl-Client-UnmemSpellAll)
* [$client->UnmemSpellBySpellID(int spell_id) # void](Perl-Client-UnmemSpellBySpellID)
* [$client->UnscribeSpell(int slot, update_client) # void](Perl-Client-UnscribeSpell)
* [$client->UnscribeSpellAll(update_client) # void](Perl-Client-UnscribeSpellAll)
* [$client->UntrainDisc(int slot, update_client) # void](Perl-Client-UntrainDisc)
* [$client->UntrainDiscAll(update_client) # void](Perl-Client-UntrainDiscAll)
* [$client->UpdateAdmin(bool iFromDB) # void](Perl-Client-UpdateAdmin)
* [$client->UpdateGroupAAs(points, int type) # void](Perl-Client-UpdateGroupAAs)
* [$client->UpdateLDoNPoints(points, theme) # bool](Perl-Client-UpdateLDoNPoints)
* [$client->UpdateTaskActivity(TaskID, ActivityID, Count, bool ignore_quest_update) # void](Perl-Client-UpdateTaskActivity)
* [$client->UpdateWho(remove) # void](Perl-Client-UpdateWho)
* [$client->UseDiscipline(int spell_id, target) # bool](Perl-Client-UseDiscipline)
* [$client->WorldKick() # void](Perl-Client-WorldKick)