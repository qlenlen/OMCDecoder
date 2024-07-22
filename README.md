# OMCDecoder

Samsung OMC Decoder implementation in C++ from CSC apk.

# Usage

```
cscdecoder [options] input.xml output.xml

Options:
    -d/--decode     Decodes input.xml and saves to output.xml (default)
    -e/--encode     Encodes input.xml and saves to output.xml
    -i/--in-place   Save output to input.xml (output.xml is ignored)
```

## Csc Feature Tweaks

> Origin repo: ravindu644/Samsung_Additional_Features


### 01. Data Icon Style (4G+) 

```
<CscFeature_SystemUI_ConfigOverrideDataIcon>DCM</CscFeature_SystemUI_ConfigOverrideDataIcon>
```

### 02. Camera Shutter Sound menu

```
<CscFeature_Camera_ShutterSoundMenu>TRUE</CscFeature_Camera_ShutterSoundMenu>
```

### 03. Enhance image quality

```
<CscFeature_Common_EnhanceImageQuality>TRUE</CscFeature_Common_EnhanceImageQuality>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
```

### 04. Mobile Data button on Power Menu

```
<CscFeature_Framework_SupportDataModeSwitchGlobalAction>TRUE</CscFeature_Framework_SupportDataModeSwitchGlobalAction>
```

### 05. Useful Cards menu in Messages

```
<CscFeature_Message_SupportUsefulcard>TRUE</CscFeature_Message_SupportUsefulcard>
```

### 06. Change 4G icon (value can be CHC, TGY, VZW, ATT, SPR, each one has different 4G icon)

```
<CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>CHC</CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>
```

<hr> - Special Thanks : <a href="https://t.me/Hiruka_NU">@Hiruka_NU</a> | <a href="https://xdaforums.com/t/csc-feature-mods.4538389/"> This post on XDA </a> | <a href="https://t.me/User7884or7885">@User7884or7885</a><br><hr>

### 07. Play songs while recording a video.

```
<CscFeature_Camera_CamcorderDoNotPauseMusic>TRUE</CscFeature_Camera_CamcorderDoNotPauseMusic>
```

### 08. Camera Tweaks

```
<CscFeature_Camera_CameraFlicker>60hz</CscFeature_Camera_CameraFlicker>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
```

### 09. Confirmation popup after tapping the quick tooggle for mobile data

```
<CscFeature_Setting_EnablePromptPopupWhenActivatingDataConnection>TRUE</CscFeature_Setting_EnablePromptPopupWhenActivatingDataConnection>
```

### 10. Data icon style(LTE)

```
<CscFeature_SystemUI_ConfigOverrideDataIcon>LTE</CscFeature_SystemUI_ConfigOverrideDataIcon>
```

### 11. Data usage in quick panel(Need China smart manager)

```
<CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>TRUE</CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>
```

### 12. Network speed meter

```
<CscFeature_Setting_SupportRealTimeNetworkSpeed>TRUE</CscFeature_Setting_SupportRealTimeNetworkSpeed>
```

- For One UI 6 and up, you will need this line too:

```
<CscFeature_Common_SupportZProjectFunctionInGlobal>TRUE</CscFeature_Common_SupportZProjectFunctionInGlobal>
```

### 13. Camera will works during a call

```
<CscFeature_Camera_EnableCameraDuringCall>TRUE</CscFeature_Camera_EnableCameraDuringCall>
```

### 14. Call Recording in Samsung Dialer

```
<CscFeature_VoiceCall_ConfigRecording>RecordingAllowedByMenu</CscFeature_VoiceCall_ConfigRecording>
```

### ¬ Smart Manager

```
<CscFeature_SmartManager_DisableAntiMalware>TRUE</CscFeature_SmartManager_DisableAntiMalware>
<CscFeature_SmartManager_ConfigDashboard>dual_dashboard</CscFeature_SmartManager_ConfigDashboard>
<CscFeature_SmartManager_ConfigSubFeatures>applock|appcleanner|autolaunch|autorestart|devicesecurity|storageclean|backgroundapp|chinadualpage|UDS|UDS2|applicationpermission|networkpowersaving|notificationmanager|trafficmanager|roguepopup|data_compression|cstyle</CscFeature_SmartManager_ConfigSubFeatures>
<CscFeature_SmartManager_ConfigUdsSubFeatures>videocompression|uploadcompression</CscFeature_SmartManager_ConfigUdsSubFeatures>
```

### ¬ SystemUI

```
<CscFeature_SystemUI_ConfigOpBranding5GIcon>5GAvailable,RRCStateCheck,UseDisplayTimer</CscFeature_SystemUI_ConfigOpBranding5GIcon>
<CscFeature_SystemUI_ConfigDefQuickSettingItem>Wifi,SilentMode,SoundMode,WindowsLink,Bluetooth,NightMode,FocusMode,Intent,ColorInversion,Ebook,Routines,InstantSession,RotationLock,PowerShare,Flashlight,QRScanner,AirplaneMode,PowerSaving,MobileData,WifiCalling,Performance,BlueLightFilter,WifiHotspot,Hotspot,PersonalMode,SecureFolder,Location,Nfc,Aod,AllShareCast,ShareLive,DeviceVisibility,Dnd,Sync,UDS,BikeMode,PowerPlanning,EdgeLighting,FloatingMessage,RedPacket,DormantMode,NetworkBooster,QuickConnect,SmartStay,SmartPause,AirView,AirBrowse,Toolbox,CarMode,UltraPowerSaving,SFinder,ScreenCapture,ScreenRecorder,VoLte,Dolby,BatteryMode,DailyBoard,DesktopMode,SpenRemote,KidsHome,GrxScreenOnTime,GrxScreenRecord,GrxMultiAction,GrxRecovery</CscFeature_SystemUI_ConfigDefQuickSettingItem>
<CscFeature_SystemUI_ConfigQuickSettingPopup>SER</CscFeature_SystemUI_ConfigQuickSettingPopup>
<CscFeature_SystemUI_ConfigOverrideDataIcon>LTE</CscFeature_SystemUI_ConfigOverrideDataIcon>
<CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>TTT</CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>
<CscFeature_SystemUI_ConfigOpBrandingForDataIndicator>TTT</CscFeature_SystemUI_ConfigOpBrandingForDataIndicator>
<CscFeature_SystemUI_SupportRecentAppProtection>TRUE</CscFeature_SystemUI_SupportRecentAppProtection>
<CscFeature_SystemUI_SupportAssistanceAppChooser>TRUE</CscFeature_SystemUI_SupportAssistanceAppChooser>
<CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>TRUE</CscFeature_SystemUI_SupportDataUsageViewOnQuickPanel>
```

### ¬ Calendar

```
<CscFeature_Calendar_EnableWeatherInfo>TRUE</CscFeature_Calendar_EnableWeatherInfo>
<CscFeature_Calendar_SetColorOfDays>XXXXXBR</CscFeature_Calendar_SetColorOfDays>
<CscFeature_Calendar_EnableMsgReminder>TRUE</CscFeature_Calendar_EnableMsgReminder>
```

### ¬ Settings

```
<CscFeature_Settings_EnableUSM>TRUE</CscFeature_Settings_EnableUSM>
<CscFeature_Setting_ConfigAddSuffixModelNumber>/DS</CscFeature_Setting_ConfigAddSuffixModelNumber>
<CscFeature_Setting_EnableMenuBlockCallMsg>TRUE</CscFeature_Setting_EnableMenuBlockCallMsg>
<CscFeature_Setting_EnableDataRoamingMenuInDetail>TRUE</CscFeature_Setting_EnableDataRoamingMenuInDetail>
<CscFeature_Setting_EnableEditingIpVersionType>TRUE</CscFeature_Setting_EnableEditingIpVersionType>
<CscFeature_Setting_EnableMenuDownloadContents>TRUE</CscFeature_Setting_EnableMenuDownloadContents>
<CscFeature_Setting_EnableRoamingMenu>TRUE</CscFeature_Setting_EnableRoamingMenu>
<CscFeature_Setting_IncludeApn4SwUpdate>TRUE</CscFeature_Setting_IncludeApn4SwUpdate>
<CscFeature_Setting_DisableMenuSoftwareUpdate>TRUE</CscFeature_Setting_DisableMenuSoftwareUpdate>
<CscFeature_Setting_CustNetworkSelMenu4>LTEONLY</CscFeature_Setting_CustNetworkSelMenu4>
<CscFeature_Setting_SupportRealTimeNetworkSpeed>TRUE</CscFeature_Setting_SupportRealTimeNetworkSpeed>
<CscFeature_Setting_DataRoamingOption>national</CscFeature_Setting_DataRoamingOption>
<CscFeature_Setting_DisableMenuFindMyMobile>TRUE</CscFeature_Setting_DisableMenuFindMyMobile>
<CscFeature_Setting_EnableDataRoamingButtonInQuickPanel>TRUE</CscFeature_Setting_EnableDataRoamingButtonInQuickPanel>
<CscFeature_Setting_EditOption4ApnType>List</CscFeature_Setting_EditOption4ApnType>
<CscFeature_Setting_ConfigAboutDeviceItems>fcc=disabled;modelnumberNFCsuffix=enabled;</CscFeature_Setting_ConfigAboutDeviceItems>
<CscFeature_Setting_InfinitySoftwareUpdate>TRUE</CscFeature_Setting_InfinitySoftwareUpdate>
<CscFeature_Setting_SkipStepsDuringSamsungSetupWizard>TRUE</CscFeature_Setting_SkipStepsDuringSamsungSetupWizard>
<CscFeature_Setting_SupportWifiCall>TRUE</CscFeature_Setting_SupportWifiCall>
<CscFeature_Settings_Reset_Password>TRUE</CscFeature_Settings_Reset_Password>
<CscFeature_Setting_SupportWiFiCallingMenu>TRUE</CscFeature_Setting_SupportWiFiCallingMenu>
<CscFeature_Setting_EnableMenuNetworkMode>TRUE</CscFeature_Setting_EnableMenuNetworkMode>
<CscFeature_Setting_SkipWifiActvDuringSetupWizard>FALSE</CscFeature_Setting_SkipWifiActvDuringSetupWizard>
<CscFeature_Setting_EnableFactoryResetPasswordWhenNoSIM>FALSE</CscFeature_Setting_EnableFactoryResetPasswordWhenNoSIM>
<CscFeature_Settings_FOTA>FALSE<CscFeature_Settings_FOTA>
<CscFeature_Settings_GOTA>TRUE</CscFeature_Settings_GOTA>
<CscFeature_Settings_FindMyMobile>FALSE</CscFeature_Settings_FindMyMobile>
```

### ¬ Clock

```
<CscFeature_Clock_ConfigDefStatusWorldclockWeather>OFF</CscFeature_Clock_ConfigDefStatusWorldclockWeather>
<CscFeature_Clock_DisableGoogleLocationInfo>TRUE</CscFeature_Clock_DisableGoogleLocationInfo>
<CscFeature_Clock_EnableAutoPowerOnOffMenu>TRUE</CscFeature_Clock_EnableAutoPowerOnOffMenu>
<CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>TRUE</CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>
<CscFeature_Clock_SupportAlarmOptionMenuForWorkingDay>TRUE</CscFeature_Clock_SupportAlarmOptionMenuForWorkingDay>
```

### ¬ Camera

```
<CscFeature_Camera_ShutterSoundMenu>TRUE</CscFeature_Camera_ShutterSoundMenu>
<CscFeature_Camera_CameraFlicker>60hz</CscFeature_Camera_CameraFlicker>
<CscFeature_Camera_EnableCameraDuringCall>TRUE</CscFeature_Camera_EnableCameraDuringCall>
<CscFeature_Camera_EnableSmsNotiPopup>TRUE</CscFeature_Camera_EnableSmsNotiPopup>
<CscFeature_Camera_DefaultQuality>superfine</CscFeature_Camera_DefaultQuality>
<CscFeature_Camera_SecurityMdmService>TRUE</CscFeature_Camera_SecurityMdmService>
<CscFeature_Camera_CamcorderDoNotPauseMusic>TRUE</CscFeature_Camera_CamcorderDoNotPauseMusic>
<CscFeature_Camera_CamcoderForceShutterSoundDuringSnapShot>FALSE</CscFeature_Camera_CamcoderForceShutterSoundDuringSnapShot>
<CscFeature_Camera_CamcorderEnablePromptPopupToSelectRecMode>TRUE</CscFeature_Camera_CamcorderEnablePromptPopupToSelectRecMode>
<CscFeature_Camcorder_DoNotPauseMusic>TRUE</CscFeature_Camcorder_DoNotPauseMusic>
<CscFeature_Camcorder_DefaultQuality>superfine</CscFeature_Camcorder_DefaultQuality>
```

### ¬ Common

```
<CscFeature_Common_DisablePhoneNumberFormatting>TRUE</CscFeature_Common_DisablePhoneNumberFormatting>
<CscFeature_Common_EulaVersion>2</CscFeature_Common_EulaVersion>
<CscFeature_Common_SupportRmm>TRUE</CscFeature_Common_SupportRmm>
<CscFeature_Common_SupportWcdmaInSlave>TRUE</CscFeature_Common_SupportWcdmaInSlave>
<CscFeature_Common_EnableHDVoiceDuring3GConnection>TRUE</CscFeature_Common_EnableHDVoiceDuring3GConnection>
<CscFeature_Common_EnableUiDisplayMirroring>TRUE</CscFeature_Common_EnableUiDisplayMirroring>
<CscFeature_Common_EnableVIPMode>TRUE</CscFeature_Common_EnableVIPMode>
<CscFeature_Common_EnableAirMessage>FALSE</CscFeature_Common_EnableAirMessage>
<CscFeature_Common_SupportDualIMS>TRUE</CscFeature_Common_SupportDualIMS>
<CscFeature_Common_AllowExternalApkUsage>TRUE</CscFeature_Common_AllowExternalApkUsage>
<CscFeature_Knox_SupportKnoxGuard>FALSE</CscFeature_Knox_SupportKnoxGuard>
```

### ¬ Voice Call

```
<CscFeature_VoiceCall_SupportShowVowifiEndCall>TRUE</CscFeature_VoiceCall_SupportShowVowifiEndCall>
<CscFeature_VoiceCall_ConfigRecording>RecordingAllowedByMenu</CscFeature_VoiceCall_ConfigRecording>
<CscFeature_VoiceCall_EnableVmsNumberAsDefaultInCallForwarding>TRUE</CscFeature_VoiceCall_EnableVmsNumberAsDefaultInCallForwarding>
<CscFeature_VoiceCall_ConfigCallforwardCfnryTimer>Remove</CscFeature_VoiceCall_ConfigCallforwardCfnryTimer>
<CscFeature_VoiceCall_ConfigOpStyleForHdIcon>XSG_HD,XSG_UHD</CscFeature_VoiceCall_ConfigOpStyleForHdIcon>
<CscFeature_VoiceCall_ConfigOpStyleForRingBackTone>SINGTEL</CscFeature_VoiceCall_ConfigOpStyleForRingBackTone>
<CscFeature_VoiceCall_DisableCallTransfer>TRUE</CscFeature_VoiceCall_DisableCallTransfer> 
<CscFeature_VoiceCall_EnableGroupCallMenu>TRUE</CscFeature_VoiceCall_EnableGroupCallMenu>
<CscFeature_VoiceCall_SupportAutoCallTest>TRUE</CscFeature_VoiceCall_SupportAutoCallTest>
<CscFeature_VoiceCall_SupportAutoDialDuringRoaming>TRUE</CscFeature_VoiceCall_SupportAutoDialDuringRoaming>
<CscFeature_VoiceCall_SupportAutoUnholdForMultiCallFinish>TRUE</CscFeature_VoiceCall_SupportAutoUnholdForMultiCallFinish>
<CscFeature_VoiceCall_SupportClearDialInputData>TRUE</CscFeature_VoiceCall_SupportClearDialInputData>
<CscFeature_VoiceCall_SupportEmergencyCallUsingVolte>TRUE</CscFeature_VoiceCall_SupportEmergencyCallUsingVolte>
<CscFeature_VoiceCall_SupportImsPsBarring>TRUE</CscFeature_VoiceCall_SupportImsPsBarring>
<CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>voltesettingscommon,checknonvoltesim,voltesettingOPS</CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>
<CscFeature_VoiceCall_SupportInterworkingHdVoiceByIntent>TRUE</CscFeature_VoiceCall_SupportInterworkingHdVoiceByIntent>
<CscFeature_VoiceCall_SupportMenuPersonaliseSoftSound>TRUE</CscFeature_VoiceCall_SupportMenuPersonaliseSoftSound>
<CscFeature_VoiceCall_SupportOpticCmdTest>TRUE</CscFeature_VoiceCall_SupportOpticCmdTest>
<CscFeature_VoiceCall_SupportPopupForDataOff>TRUE</CscFeature_VoiceCall_SupportPopupForDataOff>
```

### ¬ Voice Recorder

```
<CscFeature_VoiceRecorder_SupportPrivacyPolicyPrompt>TRUE</CscFeature_VoiceRecorder_SupportPrivacyPolicyPrompt>
```

### ¬ Contact

```
<CscFeature_Contact_EnableLogIconForVoiceRecord>TRUE</CscFeature_Contact_EnableLogIconForVoiceRecord>
<CscFeature_Contact_FullCountryPrefixSearchSupport>TRUE</CscFeature_Contact_FullCountryPrefixSearchSupport>
<CscFeature_Contact_ConfigDefaultViewBy>AllCalls</CscFeature_Contact_ConfigDefaultViewBy>
<CscFeature_Contact_DisableGoogleTalk>TRUE</CscFeature_Contact_DisableGoogleTalk>
<CscFeature_Contact_EnableCallButtonInList>TRUE</CscFeature_Contact_EnableCallButtonInList>
<CscFeature_Contact_SupportSIMContacts>TRUE</CscFeature_Contact_SupportSIMContacts>
<CscFeature_Contact_ExportAllNumberToSIM>TRUE</CscFeature_Contact_ExportAllNumberToSIM>
<CscFeature_Contact_EnableCopyToDialer>TRUE</CscFeature_Contact_EnableCopyToDialer>
<CscFeature_Contact_ExtendSpeedDialTo100>TRUE</CscFeature_Contact_ExtendSpeedDialTo100>
<CscFeature_Contact_LimitNameLength>1280</CscFeature_Contact_LimitNameLength>
<CscFeature_Contact_EnableDynCallerIdMatchingDigitWithAutoSim>TRUE</CscFeature_Contact_EnableDynCallerIdMatchingDigitWithAutoSim>
<CscFeature_Contact_SetLinkCountMaxAs>999</CscFeature_Contact_SetLinkCountMaxAs>
<CscFeature_Contact_SupportDuoVideoCall>TRUE</CscFeature_Contact_SupportDuoVideoCall>
<CscFeature_Contact_EnableExtraCallServiceMenu>TRUE</CscFeature_Contact_EnableExtraCallServiceMenu>
<CscFeature_Contact_EnableSelectableListToExportSdCard>TRUE</CscFeature_Contact_EnableSelectableListToExportSdCard>
```

### ¬ Messages

```
<CscFeature_Message_SupportUsefulcard>TRUE</CscFeature_Message_SupportUsefulcard>
<CscFeature_Message_EnablePhoneNumberFormattingInMsg>TRUE</CscFeature_Message_EnablePhoneNumberFormattingInMsg>
<CscFeature_Message_EnableEmailOverSms>TRUE</CscFeature_Message_EnableEmailOverSms>
<CscFeature_Message_EnableEditingSenderAddress>TRUE</CscFeature_Message_EnableEditingSenderAddress>
<CscFeature_Message_EnableAddContactIn1stDepthComposerOption>TRUE</CscFeature_Message_EnableAddContactIn1stDepthComposerOption>
<CscFeature_Message_CMASOperator>uae</CscFeature_Message_CMASOperator>
<CscFeature_Message_ConfigFreeMessage>OFF</CscFeature_Message_ConfigFreeMessage>
<CscFeature_Message_EnableSaveRestoreSDCard>TRUE</CscFeature_Message_EnableSaveRestoreSDCard>
<CscFeature_Message_AddSendOptionInComposer>TRUE</CscFeature_Message_AddSendOptionInComposer>
<CscFeature_Message_ConfigEmojiComposing>TRUE</CscFeature_Message_ConfigEmojiComposing>
<CscFeature_Message_ConfigSpamReport>TRUE</CscFeature_Message_ConfigSpamReport>
<CscFeature_Message_ConfigThreadForMultipleDest>TRUE</CscFeature_Message_ConfigThreadForMultipleDest>
<CscFeature_Message_DisableCBNotifications>FALSE</CscFeature_Message_DisableCBNotifications>
<CscFeature_Message_DisableConvertingEffectBetweenSMSMMS>TRUE</CscFeature_Message_DisableConvertingEffectBetweenSMSMMS>
<CscFeature_Message_DisableCopyToSim>FALSE</CscFeature_Message_DisableCopyToSim>
<CscFeature_Message_DisableDeleteButtonOnActionBar>FALSE</CscFeature_Message_DisableDeleteButtonOnActionBar>
<CscFeature_Message_DisableLogs>TRUE</CscFeature_Message_DisableLogs>
<CscFeature_Message_DisableMenuCBChannel>FALSE</CscFeature_Message_DisableMenuCBChannel>
<CscFeature_Message_DisableMenuCBMessage>FALSE</CscFeature_Message_DisableMenuCBMessage>
<CscFeature_Message_DisableMenuMmsCreationMode>FALSE</CscFeature_Message_DisableMenuMmsCreationMode>
<CscFeature_Message_DisableMenuSIMMessages>FALSE</CscFeature_Message_DisableMenuSIMMessages>
<CscFeature_Message_DisableMenuSMSC>FALSE</CscFeature_Message_DisableMenuSMSC>
<CscFeature_Message_DisableMenuSmsInputMode>FALSE</CscFeature_Message_DisableMenuSmsInputMode>
<CscFeature_Message_DisableMmsSubject>FALSE</CscFeature_Message_DisableMmsSubject>
<CscFeature_Message_DisableOptionAttachLocation>FALSE</CscFeature_Message_DisableOptionAttachLocation>
<CscFeature_Message_DisableOptionAttachVCalendar>FALSE</CscFeature_Message_DisableOptionAttachVCalendar>
<CscFeature_Message_DisableOptionAttachVCard>FALSE</CscFeature_Message_DisableOptionAttachVCard>
<CscFeature_Message_DisableOptionAttachVMemo>FALSE</CscFeature_Message_DisableOptionAttachVMemo>
<CscFeature_Message_DisableOptionRecordAudio>FALSE</CscFeature_Message_DisableOptionRecordAudio>
<CscFeature_Message_DisableSaveClassZeroMessage>FALSE</CscFeature_Message_DisableSaveClassZeroMessage>
<CscFeature_Message_DisableSaveRingtoneMenu>FALSE</CscFeature_Message_DisableSaveRingtoneMenu>
<CscFeature_Message_DisableSmscEditable>FALSE</CscFeature_Message_DisableSmscEditable>
<CscFeature_Message_DisableSmsToMmsConversionByTextInput>TRUE</CscFeature_Message_DisableSmsToMmsConversionByTextInput>
<CscFeature_Message_DisplaySmsTimeAs>TRUE</CscFeature_Message_DisplaySmsTimeAs>
<CscFeature_Message_EnableAlias>TRUE</CscFeature_Message_EnableAlias>
<CscFeature_Message_EnableAllContextMenuInMsgViewer>TRUE</CscFeature_Message_EnableAllContextMenuInMsgViewer>
<CscFeature_Message_EnableAnonymousThread>TRUE</CscFeature_Message_EnableAnonymousThread>
<CscFeature_Message_EnableBlackList>TRUE</CscFeature_Message_EnableBlackList>
<CscFeature_Message_EnableCombineAndForwardMessage>TRUE</CscFeature_Message_EnableCombineAndForwardMessage>
<CscFeature_Message_EnableContactInfoInBubble>TRUE</CscFeature_Message_EnableContactInfoInBubble>
<CscFeature_Message_EnableDbBackupKeystring>TRUE</CscFeature_Message_EnableDbBackupKeystring>
<CscFeature_Message_EnableDisplayTotalCount4SimMsg>TRUE</CscFeature_Message_EnableDisplayTotalCount4SimMsg>
<CscFeature_Message_EnableFlickThreadView>TRUE</CscFeature_Message_EnableFlickThreadView>
<CscFeature_Message_EnableFolderView>TRUE</CscFeature_Message_EnableFolderView>
<CscFeature_Message_EnableFontSize>TRUE</CscFeature_Message_EnableFontSize>
<CscFeature_Message_EnableFontSizeByVolumeKey>TRUE</CscFeature_Message_EnableFontSizeByVolumeKey>
<CscFeature_Message_EnableMenuInsertSenderInfoWhenFwdMsg>TRUE</CscFeature_Message_EnableMenuInsertSenderInfoWhenFwdMsg>
<CscFeature_Message_EnableMenuMmsDeliveryTime>TRUE</CscFeature_Message_EnableMenuMmsDeliveryTime>
<CscFeature_Message_EnableMenuMmsExpiryDate>TRUE</CscFeature_Message_EnableMenuMmsExpiryDate>
<CscFeature_Message_EnableMenuMmsPriority>TRUE</CscFeature_Message_EnableMenuMmsPriority>
<CscFeature_Message_EnableMenuRemindAlert>TRUE</CscFeature_Message_EnableMenuRemindAlert>
<CscFeature_Message_EnableMenuSendMmsDeliveryReport>TRUE</CscFeature_Message_EnableMenuSendMmsDeliveryReport>
<CscFeature_Message_EnableMenuSmsExpiryDate>FALSE</CscFeature_Message_EnableMenuSmsExpiryDate>
<CscFeature_Message_EnableMessagePriorityDuringComposing>TRUE</CscFeature_Message_EnableMessagePriorityDuringComposing>
<CscFeature_Message_EnableMessageSentTimeInSimList>TRUE</CscFeature_Message_EnableMessageSentTimeInSimList>
<CscFeature_Message_EnableMmsMobiledataOff>TRUE</CscFeature_Message_EnableMmsMobiledataOff>
<CscFeature_Message_EnableMsgTypeIndicationDuringComposing>TRUE</CscFeature_Message_EnableMsgTypeIndicationDuringComposing>
<CscFeature_Message_EnableMultiCopyToSim>TRUE</CscFeature_Message_EnableMultiCopyToSim>
<CscFeature_Message_EnableMultiDraftBox>TRUE</CscFeature_Message_EnableMultiDraftBox>
<CscFeature_Message_EnableMultiLockMenu>TRUE</CscFeature_Message_EnableMultiLockMenu>
<CscFeature_Message_EnableNotificationBroadcastReceivedMessage>TRUE</CscFeature_Message_EnableNotificationBroadcastReceivedMessage>
<CscFeature_Message_EnableRegisterToCalender>TRUE</CscFeature_Message_EnableRegisterToCalender>
<CscFeature_Message_EnableReplyAll>TRUE</CscFeature_Message_EnableReplyAll>
<CscFeature_Message_BlockSendMmsWithOnlySubject>TRUE</CscFeature_Message_BlockSendMmsWithOnlySubject>
<CscFeature_Message_EnableSaveVMessage>TRUE</CscFeature_Message_EnableSaveVMessage>
<CscFeature_Message_SupportAutoDeleteSpam>TRUE</CscFeature_Message_SupportAutoDeleteSpam>
<CscFeature_Message_EnableScheduledMessage>TRUE</CscFeature_Message_EnableScheduledMessage>
<CscFeature_Message_EnableScheduledMsgBox>TRUE</CscFeature_Message_EnableScheduledMsgBox>
<CscFeature_Message_EnableSearchByInitialConsonant>TRUE</CscFeature_Message_EnableSearchByInitialConsonant>
<CscFeature_Message_EnableSendingEmptySms>TRUE</CscFeature_Message_EnableSendingEmptySms>
<CscFeature_Message_EnableSmsCallbackNumber>TRUE</CscFeature_Message_EnableSmsCallbackNumber>
<CscFeature_Message_EnableSmsForwardPrefix>TRUE</CscFeature_Message_EnableSmsForwardPrefix>
<CscFeature_Message_EnableSMSPcheckWhenSendSMS>TRUE</CscFeature_Message_EnableSMSPcheckWhenSendSMS>
<CscFeature_Message_EnableSpeedDial>TRUE</CscFeature_Message_EnableSpeedDial>
<CscFeature_Message_EnableTextFieldColor>TRUE</CscFeature_Message_EnableTextFieldColor>
<CscFeature_Message_EnableVCard>TRUE</CscFeature_Message_EnableVCard>
<CscFeature_Message_EnableViewByMessageType>TRUE</CscFeature_Message_EnableViewByMessageType>
<CscFeature_Message_MaxSlideCount>999</CscFeature_Message_MaxSlideCount>
<CscFeature_Message_RecipientLimit>999</CscFeature_Message_RecipientLimit>
<CscFeature_Message_SmsToMmsTextThreshold>999</CscFeature_Message_SmsToMmsTextThreshold>
<CscFeature_Message_SmsMaxByte>999</CscFeature_Message_SmsMaxByte>
<CscFeature_Message_ReplaceCRToNewLine>TRUE</CscFeature_Message_ReplaceCRToNewLine>
<CscFeature_Message_ReplaceLabel4RetreivedMsg>TRUE</CscFeature_Message_ReplaceLabel4RetreivedMsg>
<CscFeature_Message_SmsInputMode>automatic</CscFeature_Message_SmsInputMode>
```

### ¬ NFC

```
<CscFeature_NFC_FollowTechnologyRouteToDefRoute>TRUE</CscFeature_NFC_FollowTechnologyRouteToDefRoute>
<CscFeature_NFC_DefStatus>OFF</CscFeature_NFC_DefStatus>
<CscFeature_NFC_StatusBarIconType>DEFAULT</CscFeature_NFC_StatusBarIconType>
```

### ¬ Weather

> CMA refers to CHN, while TWC refers to TGY

```
<CscFeature_Weather_ConfigCpType>TWC</CscFeature_Weather_ConfigCpType>
<CscFeature_Weather_SupportCheckingDisputeArea>TRUE</CscFeature_Weather_SupportCheckingDisputeArea>
```

### ¬ VoLTE

```
<CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>voltesettingscommon,checknonvoltesim,voltesettingOPS</CscFeature_VoiceCall_ConfigOpStyleForMobileNetSetting>
```

### ¬ Framework

```
<CscFeature_Framework_ReplaceDataTypeIconAsOpBrand>LTE</CscFeature_Framework_ReplaceDataTypeIconAsOpBrand>
<CscFeature_Framework_SupportDataModeSwitchGlobalAction>TRUE</CscFeature_Framework_SupportDataModeSwitchGlobalAction>
```

### ¬ GPS

```
<CscFeature_GPS_SupportPrivacyLock>TRUE</CscFeature_GPS_SupportPrivacyLock>
<CscFeature_GPS_SupportGoogleSupl2>TRUE</CscFeature_GPS_SupportGoogleSupl2>
```

### ¬ IMS

```
<CscFeature_IMS_EnableVoLTE>TRUE</CscFeature_IMS_EnableVoLTE>
```

### ¬ Launcher

```
<CscFeature_Launcher_DisableFastScrollIndex>TRUE</CscFeature_Launcher_DisableFastScrollIndex>
<CscFeature_Launcher_AddAutoRotationIcon>TRUE</CscFeature_Launcher_AddAutoRotationIcon>
<CscFeature_Launcher_SupportBadgeClearGesture>TRUE</CscFeature_Launcher_SupportBadgeClearGesture>
<CscFeature_Launcher_ConfigMagazineHome>off</CscFeature_Launcher_ConfigMagazineHome>
<CscFeature_Launcher_PerformanceTunning>TRUE</CscFeature_Launcher_PerformanceTunning>
```

### ¬ Music

```
<CscFeature_Music_SupportPlaybackDuringCall>TRUE</CscFeature_Music_SupportPlaybackDuringCall>
<CscFeature_MediaProvider_HideVoiceFilesInMusic>TRUE</CscFeature_MediaProvider_HideVoiceFilesInMusic>
<CscFeature_Music_TranslateUnknownTitle>TRUE</CscFeature_Music_TranslateUnknownTitle>
```

### ¬ My Files

```
<CscFeature_MyFiles_SupportApkCategory>TRUE</CscFeature_MyFiles_SupportApkCategory>
<CscFeature_MyFiles_SupportFolderDescription>TRUE</CscFeature_MyFiles_SupportFolderDescription>
```

### ¬ SyncML

```
<CscFeature_SyncML_DiscardCpSecurityType4>Userpin,Usernetwpin,None</CscFeature_SyncML_DiscardCpSecurityType4>
```

### ¬ Web

```
<CscFeature_Web_AddOptionToTerminate>TRUE</CscFeature_Web_AddOptionToTerminate>
<CscFeature_Web_ConfigSyncSource>TRUE</CscFeature_Web_ConfigSyncSource>
<CscFeature_Web_bool_EnablePriorityUserBookmark>FALSE</CscFeature_Web_bool_EnablePriorityUserBookmark>
<CscFeature_Web_EnableMaxTabs>1000</CscFeature_Web_EnableMaxTabs>
<CscFeature_Web_EnablePromptToExit>TRUE</CscFeature_Web_EnablePromptToExit>
<CscFeature_Web_SetHomepageURL>https://forum.xda-developers.com/member.php?u=10949429</CscFeature_Web_SetHomepageURL>
```

### ¬ Wifi

```
<CscFeature_Wifi_MaxClient4MobileAp>10</CscFeature_Wifi_MaxClient4MobileAp>
<CscFeature_Wifi_SetCountryInfo>TRUE</CscFeature_Wifi_SetCountryInfo>
<CscFeature_Wifi_SupportAdvancedMenu>TRUE</CscFeature_Wifi_SupportAdvancedMenu>
<CscFeature_Wifi_SupportMobileApOnTrigger>TRUE</CscFeature_Wifi_SupportMobileApOnTrigger>
<CscFeature_Wifi_ConfigSnsStatus>DEFAULT_ON</CscFeature_Wifi_ConfigSnsStatus>
<CscFeature_Wifi_ConfigSecureSvcIntegration>TencentSecurityWiFi</CscFeature_Wifi_ConfigSecureSvcIntegration>
<CscFeature_Wifi_SupportSecureWifi>FALSE</CscFeature_Wifi_SupportSecureWifi>
```

### ¬ Lockscreen

```
<CscFeature_LockScreen_ConfigCarrierSecurityPolicy>SupportSimPermanentDisable</CscFeature_LockScreen_ConfigCarrierSecurityPolicy>
<CscFeature_LockScreen_ConfigClockDisplayPolicy>ShowRomaingTime</CscFeature_LockScreen_ConfigClockDisplayPolicy>
```

# Build.prop Tweaks

Add these lines in Build.prop, which is located in system/system. (Some probably is placebo i haven't tested all of them)

### 01. Circle to search A14+

```
ro.com.google.cdb.spa1=bsxasm1
ro.bbt.support.circle2search=true
```

> [!NOTE]  
>
> - These two circle to search build.prop codes aren't enough to enable circle2search, it requires framework & device support, but it's also a part of circle to search that's why it's given here.

### 02. Camera Tweaks -> Improves audio and video recording quality

```
ro.media.enc.jpeg.quality=100
ro.media.dec.jpeg.memcap=8000000
ro.media.enc.hprof.vid.bps=8000000
ro.media.capture.maxres=8m
ro.media.panorama.defres=3264×1840
ro.media.panorama.frameres=1280×720
ro.camcorder.videoModes=true
ro.media.enc.hprof.vid.fps=65
ro.camera.enableCamera1MaxZsl=1
camera.disable_zsl_mode=1
```

### 03. Better display quality, lower performance.

```
persist.sys.use_dithering=1
```

### 04. Faster streaming videos

```media.stagefright.enable-player=true
media.stagefright.enable-meta=true
media.stagefright.enable-scan=true
media.stagefright.enable-http=true
media.stagefright.enable-rtsp=true
media.stagefright.enable-record=false
```

### 05. Disables built in error reporting.

```
profiler.force_disable_err_rpt=1
profiler.force_disable_ulog=1
```

### 06. Better net speeds.

```
net.tcp.buffersize.default=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.wifi=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.umts=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.gprs=4096,87380,256960,4096,16384,256960
net.tcp.buffersize.edge=4096,87380,256960,4096,16384,256960
```

### 07. Disables logcat

```
logcat.live=disable
```

### 08. Phone rings immediately.

```
ro.telephony.call_ring.delay=0
ring.delay=0
```

### 09. Better call voice quality.

```
ro.ril.enable.amr.wideband=1
```

### 10. Better signal.

```
persist.cust.tel.eons=1
ro.config.hw_fast_dormancy=1
```

### 11. Disable notification while adb is active

```
persist.adb.notify=0
```

### 12. General Performance

```
debug.sf.hw=1
persist.sys.ui.hw=1
```

### 13. Saves power

```
ro.ril.disable.power.collapse=1
pm.sleep_mode=1
windowsmgr.max_events_per_sec=60
wifi.supplicant_scan_interval=180
```

### 14. Faster boot time

```
persist.sys.shutdown.mode=hibernate
ro.config.hw_quickpoweron=true
```

### 15. Better Responsiveness & Speed 

```
windowsmgr.max_events_per_sec=300
ro.max.fling_velocity=15000 
ro.min.fling_velocity=8000 
ro.min_pointer_dur=8
touch.pressure.scale=0.1
```

### 16. Video Acceleration Enabled And HW debugging (Will improve performance)

```
debug.hwui.renderer=skiagl
video.accelerate.hw=1
debug.sf.hw=1
debug.performance.tuning=1
debug.egl.hw=1
debug.composition.type=gpu
```

### 17. Disable Knox (try at your own risk!)

```
ro.config.knox=0
ro.config.iccc_version=0
ro.config.knox.ucm=0
```

Credit: <a href="https://xdaforums.com/t/tweaks-guide-build-prop-tweaks.3376962/">@XDA
</a> | [This post](https://xdaforums.com/t/tweaks-for-the-build-prop.3456214/) <hr>

### 18. Enable Zygote preforking

```
persist.device_config.runtime_native.usap_pool_enabled=true
```

### ¬ Enable Multi User

```
fw.max_users=5
fw.show_multiuserui=1
fw.showhiddenusers=1 
fw.poweruserswitcher=1
```

### 19. Enable Google Assistant

```
ro.opa.eligible_device=true
```

> [!NOTE]  
>
> - This code will enable Google Assistant 2.0 the new one for all devices, requires Google Assistant supported Google version.

### ¬ SafetyNET Fix

```
ro.knox.enhance.zygote.aslr=1
```

### 20.  Enable Multi Sim

```
ro.multisim.simslotcount=2
```

### 21.  Disable Knox

```
ro.securestorage.knox=false
```

### 22.  RMM Fix

```
ro.security.vaultkeeper.native=0
```

### 23.  Disable Locating

```
ro.com.google.locationfeatures=0
ro.com.google.networklocation=0
```

### 24. Enable Secure Storage

```
ro.securestorage.support=false
```

### 25.  ADB Fix

```
persist.adb.notify=0
persist.service.adb.enable=1
persist.sys.usb.config=mtp,adb
persist.service.debuggable=1
```

### 26. Enable Fast Dormancy

```
ro.fast.dormancy=1
ro.config.hw_fast_dormancy=1
ro.ril.fast.dormancy.rule=1
ro.semc.enable.fast_dormancy=true
```

### 27. Force GPU Rendering on 2d Operations

```
debug.sf.hw=1
debug.egl.profiler=1
debug.egl.hw=1
```

### 28. Call Delay Fix

```
ro.telephony.call.ring.delay=0
ring.delay=0
```

### 29. Increase Time Duration For WiFi scanning

```
wifi.supplicant_scan_interval=XXX
```

### 30. Save Battery Without Performance Drop

```
pm.sleep_mode=1
ro.ril.disable.power.collapse=0
wifi.supplicant_scan_interval=180
```

### 31. Fps cap remover

```
debug.gr.swapinterval=0
ro.fps_enable=1
ro.fps.capsmin=40fps
ro.fps.capsmax=60fps
cpu.fps=60
gpu.fps=60
```

### 32. Faster Booting (Might create pressure in ram)

```
ro.config.hw_quickpoweron=true
```

### 33. Enable Vulkan

```
ro.hwui.use_vulkan=1
```

### 34. Audio Improvements

```
vendor.audio.media.stereo.control=0
persist.audio.dualmic.config=endfire
persist.audio.fluence.mode=endfire
persist.audio.fluence.voicecall=true
persist.vendor.audio.fluence.voicecomm=true
persist.audio.fluence.voicerec=false
persist.audio.fluence.speaker=true
audio.deep_buffer.media=true
vendor.voice.conc.fallbackpath=deep-buffer
ro.media.dec.aud.mp3.enabled=1
ro.media.enc.aud.mp3.enabled=1
ro.media.dec.aud.flac.enabled=1
ro.media.enc.aud.flac.enabled=1
ro.media.dec.aud.wma.enabled=1
ro.media.enc.aud.wma.enabled=1
media.aac_51_output_enabled=true
flac.sw.decoder.24bit.support=true
persist.audio.speaker.dualmode=true
vendor.audio.playback.mch.downsample=true
vendor.audio.use.sw.alac.decoder=true
vendor.audio.use.sw.ape.decoder=true
af.fast_track_multiplier=1
```

### 35. Enable Webcam support for OneUI6.0+

```
ro.usb.uvc.enabled=true
```

> [!NOTE]  
>
> - Requires kernel support & plugins.

### 36. Enable Angle Support OneUi6.0+

```
ro.gfx.angle.supported=true
```

### 37. Change User interface like Tablet

```
ro.build.characteristics=tablet
```

# 实现Samsung非国行固件本地化功能

>  repo: nucked/Samsung-firmware-China-localization

##### 加入黄页

```
<CscFeature_Contact_ConfigForYellowPage>SHOW</CscFeature_Contact_ConfigForYellowPage>
```

`priv-app/SamsungYellowPage/SamsungYellowPage.apk`

##### 设置日历颜色

```
<CscFeature_Calendar_SetColorOfDays>XXXXXBR</CscFeature_Calendar_SetColorOfDays>
```

##### 启用中国假期日历

```
<CscFeature_Calendar_EnableLocalHolidayDisplay>CHINA</CscFeature_Calendar_EnableLocalHolidayDisplay>
```

##### 启用农历

```
<CscFeature_Calendar_EnableLunar>TRUE</CscFeature_Calendar_EnableLunar>
```

##### 通话中使用摄像头

```
<CscFeature_Camera_EnableCameraDuringCall>TRUE</CscFeature_Camera_EnableCameraDuringCall>
```


##### 启用自动排列图标：

```
<CscFeature_Launcher_SupportAutoIconAlign>TRUE</CscFeature_Launcher_SupportAutoIconAlign>
```


##### 启用通话录音：

```
<CscFeature_VoiceCall_ConfigRecording>RecordingAllowed</CscFeature_VoiceCall_ConfigRecording>
```

##### 天气换源：

> CMA对应中国，TGY对应香港；这一条实测6.1上没有效果

```
<CscFeature_Weather_ConfigCpType>CMA</CscFeature_Weather_ConfigCpType>
```

##### 相机快门声音开关：

> 同样的，6.1未生效

```
<CscFeature_Camera_ShutterSoundMenu>TRUE</CscFeature_Camera_ShutterSoundMenu>
```


##### SyncMl保留，其余全部删掉

```
<CscFeature_SyncML_ConfigDevicePreId>IMEI</CscFeature_SyncML_ConfigDevicePreId>
```


##### 运营商版本

```
<CscFeature_SystemUI_ConfigOpBranding5GIcon>5GAvailable,RRCStateCheck,UseOneShapedIcon,UseDisplayTimer</CscFeature_SystemUI_ConfigOpBranding5GIcon>
<CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>CHC</CscFeature_SystemUI_ConfigOpBrandingForIndicatorIcon>
<CscFeature_SystemUI_ConfigOpBrandingForQuickSettingLabel>CHC</CscFeature_SystemUI_ConfigOpBrandingForQuickSettingLabel>
<CscFeature_SystemUI_ConfigOpBrandingQuickSettingIcon>CHC</CscFeature_SystemUI_ConfigOpBrandingQuickSettingIcon>
```

##### Volte

```
<CscFeature_VoiceCall_ConfigOpStyleForVolte>VolteCtc,CTC_VOLTE,wait_for_volte_regi_in_airplane_mode_ctc</CscFeature_VoiceCall_ConfigOpStyleForVolte>
```

##### 加入网速显示

> 可能需要国行智能管理器的支持

```
<CscFeature_Setting_SupportRealTimeNetworkSpeed>TRUE</CscFeature_Setting_SupportRealTimeNetworkSpeed>
```

##### 闹钟响起前开机

```
<CscFeature_Clock_EnableAutoPowerOnOffMenu>TRUE</CscFeature_Clock_EnableAutoPowerOnOffMenu>
<CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>TRUE</CscFeature_Clock_ExclusiveEnablingAutoPowerSetting>
```


##### Bixby识屏移植 via:酷安@三星忠实头号黑粉

复制国行ROM

```
/system/system/priv-app/BixbyTouch
/system/system/etc/sysconfig/bixbytouchapp.xml
/system/system/etc/permissions/privapp-permissions-com.samsung.android.bixbytouch.xml
```

`/vendor/etc/floating_feature.xml`文件里面加入

```
<SEC_FLOATING_FEATURE_COMMON_SUPPORT_BIXBY_TOUCH>TRUE</SEC_FLOATING_FEATURE_COMMON_SUPPORT_BIXBY_TOUCH>
```

##### 加入自动开关机功能

`/vendor/etc/floating_feature.xml`文件里面加入

```
<SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_AUTO_POWER_ON_OFF>TRUE</SEC_FLOATING_FEATURE_SETTINGS_SUPPORT_AUTO_POWER_ON_OFF>
```

##### 加入来电归属地

```
/system/system/priv-app/PhoneNumberLocatorService/PhoneNumberLocatorService.apk
/system/system/etc/sysconfig/phonenumberlocatorservice.xml
/system/system/etc/permissions/privapp-permissions-com.sgmc.phonenumberlocatorservice.xml
```

###### 智慧主页

```
system/system/app/MinusOnePage
```

##### Bixby主页

```
/system/system/priv-app/BixbyHomeCN_Disable
/system/system/etc/permissions/privapp-permissions-bixbyhomecn.xml
```

##### 加入智能管理器

TGY

```
/system/priv-app/SmartManager_v5/SmartManager_v5.apk
/system/priv-app/SmartManager_v6_DeviceSecurity/SmartManager_v6_DeviceSecurity.apk
```

CHN

```
/system/system/priv-app/SmartManager_v6_DeviceSecurity_CN
/system/system/priv-app/SmartManagerCN
```

到相同目录
修改`/vendor/etc/floating_feature.xml` and `/system/etc/floating_feature.xml` 
把SMARTMANAGER_CONFIG_PACKAGE_NAME段改成

```
<SEC_FLOATING_FEATURE_SMARTMANAGER_CONFIG_PACKAGE_NAME>com.samsung.android.sm_cn</SEC_FLOATING_FEATURE_SMARTMANAGER_CONFIG_PACKAGE_NAME>
```

把SECURITY_CONFIG_DEVICEMONITOR_PACKAGE_NAME段改成

```
<SEC_FLOATING_FEATURE_SECURITY_CONFIG_DEVICEMONITOR_PACKAGE_NAME>com.samsung.android.sm.devicesecurity.tcm</SEC_FLOATING_FEATURE_SECURITY_CONFIG_DEVICEMONITOR_PACKAGE_NAME>
```

复制国行ROM  

```
/system/system/etc/permissions/privapp-permissions-com.samsung.android.sm_cn.xml
/system/system/etc/permissions/privapp-permissions-com.samsung.android.sm.devicesecurity.tcm_v6.xml
```


##### 加入骚扰拦截

```
/system/system/etc/permissions/privapp-permissions-com.sec.android.app.firewall.xml
/system/system/priv-app/Firewall
```


##### 加入应用程序锁定

复制复制国行ROM

 ```
/system/system/priv-app/AppLock
/system/system/etc/permissions/privapp-permissions-com.samsung.android.applock.xml
 ```

CSC增加subfeature

##### 更改SPen翻译为百度翻译

修改`/optics/configs/carriers/single/KOO/conf/cscfeature.xml`加入

```
<CscFeature_SPen_ConfigDefTranslatorSolution>Baidu</CscFeature_SPen_ConfigDefTranslatorSolution>
```
