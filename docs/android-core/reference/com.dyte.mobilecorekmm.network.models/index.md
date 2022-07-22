[io.dyte.core.network.models](index.md)

# Package com.dyte.mobilecorekmm.network.models

## Types

| Name | Summary |
|---|---|
| [Auth](-auth/index.md) | <br/>data class [Auth](-auth/index.md)(val userAdded: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), val authToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [Authorization](-authorization/index.md) | <br/>data class [Authorization](-authorization/index.md)(val waitingRoom: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [AuthResponse](-auth-response/index.md) | <br/>data class [AuthResponse](-auth-response/index.md)(val authResponse: [Auth](-auth/index.md)) |
| [ChatPrivatePermissions](-chat-private-permissions/index.md) | <br/>data class [ChatPrivatePermissions](-chat-private-permissions/index.md)(val canSend: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canReceive: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val text: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val files: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [ChatPublicPermissions](-chat-public-permissions/index.md) | <br/>data class [ChatPublicPermissions](-chat-public-permissions/index.md)(val canSend: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val text: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val files: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [CreateMeetingRequest](-create-meeting-request/index.md) | <br/>data class [CreateMeetingRequest](-create-meeting-request/index.md)(val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val presetName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val authorization: [Authorization](-authorization/index.md)) |
| [CreateMeetingResponse](-create-meeting-response/index.md) | <br/>data class [CreateMeetingResponse](-create-meeting-response/index.md)(val meeting: [MeetingResponse](-meeting-response/index.md)) |
| [CreateMeetingResponseWrapper](-create-meeting-response-wrapper/index.md) | <br/>data class [CreateMeetingResponseWrapper](-create-meeting-response-wrapper/index.md)(val data: [CreateMeetingResponse](-create-meeting-response/index.md)) |
| [CreateParticipantRequest](-create-participant-request/index.md) | <br/>data class [CreateParticipantRequest](-create-participant-request/index.md)(val clientSpecificId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val displayName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val presetName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val meetingId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?, val isHost: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [CreateParticipantResponseWrapper](-create-participant-response-wrapper/index.md) | <br/>data class [CreateParticipantResponseWrapper](-create-participant-response-wrapper/index.md)(val data: [AuthResponse](-auth-response/index.md)) |
| [FeaturesData](-features-data/index.md) | <br/>data class [FeaturesData](-features-data/index.md)(val logrocket: [FeaturesOrganizationModelWrapper](-features-organization-model-wrapper/index.md)?, val newCallstatsOrganization: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[FeaturesOrganizationModelWrapper](-features-organization-model-wrapper/index.md)&gt;?) |
| [FeaturesOrganizationModel](-features-organization-model/index.md) | <br/>data class [FeaturesOrganizationModel](-features-organization-model/index.md)(val organization: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;?) |
| [FeaturesOrganizationModelWrapper](-features-organization-model-wrapper/index.md) | <br/>data class [FeaturesOrganizationModelWrapper](-features-organization-model-wrapper/index.md)(val wrapper: [FeaturesOrganizationModel](-features-organization-model/index.md)?, val config: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [GraphQlRequest](-graph-ql-request/index.md) | <br/>data class [GraphQlRequest](-graph-ql-request/index.md)(val query: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val variables: [GraphQlRequestVariables](-graph-ql-request-variables/index.md)) |
| [GraphQlRequestVariables](-graph-ql-request-variables/index.md) | <br/>data class [GraphQlRequestVariables](-graph-ql-request-variables/index.md)(val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [IceServerData](-ice-server-data/index.md) | <br/>data class [IceServerData](-ice-server-data/index.md)(val url: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val username: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val credential: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val credentialType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [IceServersWrapper](-ice-servers-wrapper/index.md) | <br/>data class [IceServersWrapper](-ice-servers-wrapper/index.md)(val iceServers: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[IceServerData](-ice-server-data/index.md)&gt;) |
| [MeetingResponse](-meeting-response/index.md) | <br/>data class [MeetingResponse](-meeting-response/index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val status: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val createdAt: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [MeetingSessionData](-meeting-session-data/index.md) | <br/>data class [MeetingSessionData](-meeting-session-data/index.md)(val title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val roomNodeLink: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val password: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [MeetingSessionDataWrapper](-meeting-session-data-wrapper/index.md) | <br/>data class [MeetingSessionDataWrapper](-meeting-session-data-wrapper/index.md)(val data: [MeetingSessionWrapper](-meeting-session-wrapper/index.md)) |
| [MeetingSessionWrapper](-meeting-session-wrapper/index.md) | <br/>data class [MeetingSessionWrapper](-meeting-session-wrapper/index.md)(val session: [MeetingSessionData](-meeting-session-data/index.md)) |
| [PresignedUrlData](-presigned-url-data/index.md) | <br/>data class [PresignedUrlData](-presigned-url-data/index.md)(val putLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val getLocation: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [PresignedUrlRequest](-presigned-url-request/index.md) | <br/>data class [PresignedUrlRequest](-presigned-url-request/index.md)(val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), val filename: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?) |
| [PresignedUrlResponse](-presigned-url-response/index.md) | <br/>data class [PresignedUrlResponse](-presigned-url-response/index.md)(val data: [PresignedUrlData](-presigned-url-data/index.md)) |
| [RecordingData](-recording-data/index.md) | <br/>data class [RecordingData](-recording-data/index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [RecordingDataWrapper](-recording-data-wrapper/index.md) | <br/>data class [RecordingDataWrapper](-recording-data-wrapper/index.md)(val recording: [RecordingData](-recording-data/index.md)) |
| [StartRecordingResponseWrapper](-start-recording-response-wrapper/index.md) | <br/>data class [StartRecordingResponseWrapper](-start-recording-response-wrapper/index.md)(val data: [RecordingDataWrapper](-recording-data-wrapper/index.md)) |
| [StopRecordingModel](-stop-recording-model/index.md) | <br/>data class [StopRecordingModel](-stop-recording-model/index.md)(val recordingAction: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [UserData](-user-data/index.md) | <br/>data class [UserData](-user-data/index.md)(val id: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val email: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val picture: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val loggedIn: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val clientSpecificId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val organizationId: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserDataWrapper](-user-data-wrapper/index.md) | <br/>data class [UserDataWrapper](-user-data-wrapper/index.md)(val user: [UserData](-user-data/index.md)) |
| [UserPresetAloneHereTheme](-user-preset-alone-here-theme/index.md) | <br/>data class [UserPresetAloneHereTheme](-user-preset-alone-here-theme/index.md)(var isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetChatPermissionProps](-user-preset-chat-permission-props/index.md) | <br/>data class [UserPresetChatPermissionProps](-user-preset-chat-permission-props/index.md)(val chatPublicProps: [ChatPublicPermissions](-chat-public-permissions/index.md)? = null, val chatPrivateProps: [ChatPrivatePermissions](-chat-private-permissions/index.md)? = null) |
| [UserPresetColorsTheme](-user-preset-colors-theme/index.md) | <br/>data class [UserPresetColorsTheme](-user-preset-colors-theme/index.md)(var primary: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var secondary: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var text: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var background: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var textPrimary: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var videoBackground: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetControlBarTheme](-user-preset-control-bar-theme/index.md) | <br/>data class [UserPresetControlBarTheme](-user-preset-control-bar-theme/index.md)(var isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var elements: [UserPresetControlBarThemeElements](-user-preset-control-bar-theme-elements/index.md)? = null) |
| [UserPresetControlBarThemeElements](-user-preset-control-bar-theme-elements/index.md) | <br/>data class [UserPresetControlBarThemeElements](-user-preset-control-bar-theme-elements/index.md)(var plugins: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var screenshare: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var invite: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var participants: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var chat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var reactions: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var polls: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var fullscreen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var layout: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetData](-user-preset-data/index.md) | <br/>data class [UserPresetData](-user-preset-data/index.md)(val preset: [UserPresetModel](-user-preset-model/index.md)? = null) |
| [UserPresetDataWrapper](-user-preset-data-wrapper/index.md) | <br/>data class [UserPresetDataWrapper](-user-preset-data-wrapper/index.md)(val success: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val data: [UserPresetData](-user-preset-data/index.md)? = null) |
| [UserPresetGridTheme](-user-preset-grid-theme/index.md) | <br/>data class [UserPresetGridTheme](-user-preset-grid-theme/index.md)(var multi: [UserPresetMultiTheme](-user-preset-multi-theme/index.md)? = null, var single: [UserPresetSingleTheme](-user-preset-single-theme/index.md)? = null, var defaultView: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetHeaderTheme](-user-preset-header-theme/index.md) | <br/>data class [UserPresetHeaderTheme](-user-preset-header-theme/index.md)(var isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var elements: [UserPresetHeaderThemeElements](-user-preset-header-theme-elements/index.md)? = null) |
| [UserPresetHeaderThemeElements](-user-preset-header-theme-elements/index.md) | <br/>data class [UserPresetHeaderThemeElements](-user-preset-header-theme-elements/index.md)(var logo: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, var timer: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var title: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var participantCount: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var changeLayout: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetModel](-user-preset-model/index.md) | <br/>data class [UserPresetModel](-user-preset-model/index.md)(val permissions: [UserPresetPermissionsModel](-user-preset-permissions-model/index.md)? = null, val theme: [UserPresetThemeModel](-user-preset-theme-model/index.md)? = null, val version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val presetName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetMultiTheme](-user-preset-multi-theme/index.md) | <br/>data class [UserPresetMultiTheme](-user-preset-multi-theme/index.md)(var maxVideoCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, var videoFit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetPermissionsModel](-user-preset-permissions-model/index.md) | <br/>data class [UserPresetPermissionsModel](-user-preset-permissions-model/index.md)(val viewType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val acceptWaitingRequests: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val requestProduce: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canAllowParticipantAudio: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canAllowParticipantScreensharing: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canAllowParticipantVideo: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val requestKickParticipant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val kickParticipant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val pinParticipant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canRecord: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val waitingRoomType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val plugins: [UserPresetPluginPermissions](-user-preset-plugin-permissions/index.md)? = null, val polls: [UserPresetPollsPermissions](-user-preset-polls-permissions/index.md)? = null, val produce: [UserPresetProducePermissions](-user-preset-produce-permissions/index.md)? = null, val chat: [UserPresetChatPermissionProps](-user-preset-chat-permission-props/index.md)? = null, val reactions: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val hiddenParticipant: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val showParticipantList: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canChangeParticipantRole: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canChangeTheme: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canPresent: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val acceptPresentRequests: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canEditDisplayName: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val isRecorder: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetPluginConfig](-user-preset-plugin-config/index.md) | <br/>class [UserPresetPluginConfig](-user-preset-plugin-config/index.md) |
| [UserPresetPluginPermissions](-user-preset-plugin-permissions/index.md) | <br/>data class [UserPresetPluginPermissions](-user-preset-plugin-permissions/index.md)(val canClose: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canStart: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canEditAcl: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val config: [UserPresetPluginConfig](-user-preset-plugin-config/index.md)? = null) |
| [UserPresetPollsPermissions](-user-preset-polls-permissions/index.md) | <br/>data class [UserPresetPollsPermissions](-user-preset-polls-permissions/index.md)(val canCreate: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canVote: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val canView: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetProducePermissions](-user-preset-produce-permissions/index.md) | <br/>data class [UserPresetProducePermissions](-user-preset-produce-permissions/index.md)(val video: [UserPresetVideoPermissions](-user-preset-video-permissions/index.md)? = null, val audio: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val screenshare: [UserPresetScreenSharePermissions](-user-preset-screen-share-permissions/index.md)? = null) |
| [UserPresetRequestModel](-user-preset-request-model/index.md) | <br/>data class [UserPresetRequestModel](-user-preset-request-model/index.md)(val authToken: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val clientType: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val roomName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val version: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetScreenSharePermissions](-user-preset-screen-share-permissions/index.md) | <br/>data class [UserPresetScreenSharePermissions](-user-preset-screen-share-permissions/index.md)(val allow: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val quality: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |
| [UserPresetSetupScreenTheme](-user-preset-setup-screen-theme/index.md) | <br/>data class [UserPresetSetupScreenTheme](-user-preset-setup-screen-theme/index.md)(var isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |
| [UserPresetSingleTheme](-user-preset-single-theme/index.md) | <br/>data class [UserPresetSingleTheme](-user-preset-single-theme/index.md)(var maxVideoCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null, var videoFit: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null) |
| [UserPresetThemeModel](-user-preset-theme-model/index.md) | <br/>data class [UserPresetThemeModel](-user-preset-theme-model/index.md)(var setupScreen: [UserPresetSetupScreenTheme](-user-preset-setup-screen-theme/index.md)? = null, var aloneHere: [UserPresetAloneHereTheme](-user-preset-alone-here-theme/index.md)? = null, var waitingRoom: [UserPresetWaitingRoomTheme](-user-preset-waiting-room-theme/index.md)? = null, var controlBar: [UserPresetControlBarTheme](-user-preset-control-bar-theme/index.md)? = null, var header: [UserPresetHeaderTheme](-user-preset-header-theme/index.md)? = null, var pipMode: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var autoTune: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var grid: [UserPresetGridTheme](-user-preset-grid-theme/index.md)? = null, var colors: [UserPresetColorsTheme](-user-preset-colors-theme/index.md)? = null) |
| [UserPresetVideoPermissions](-user-preset-video-permissions/index.md) | <br/>data class [UserPresetVideoPermissions](-user-preset-video-permissions/index.md)(val allow: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, val quality: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null, val frameRate: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null) |
| [UserPresetWaitingRoomTheme](-user-preset-waiting-room-theme/index.md) | <br/>data class [UserPresetWaitingRoomTheme](-user-preset-waiting-room-theme/index.md)(var isEnabled: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null, var enablePreview: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? = null) |