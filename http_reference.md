Here is a categorized list of BlueSky endpoints based on functionality and domain.
The list helps streamline understanding and makes it easier to identify the purpose and grouping of each endpoint from the [BlueSky HTTP reference](https://docs.bsky.app/docs/category/http-reference).

---

### **Actor Management**
- **Preferences:**
  - [app.bsky.actor.getPreferences](https://docs.bsky.app/docs/api/app-bsky-actor-get-preferences)
  - [app.bsky.actor.putPreferences](https://docs.bsky.app/docs/api/app-bsky-actor-put-preferences)
- **Profiles:**
  - [app.bsky.actor.getProfile](https://docs.bsky.app/docs/api/app-bsky-actor-get-profile)
  - [app.bsky.actor.getProfiles](https://docs.bsky.app/docs/api/app-bsky-actor-get-profiles)
  - [app.bsky.actor.getSuggestions](https://docs.bsky.app/docs/api/app-bsky-actor-get-suggestions)
  - [app.bsky.actor.searchActorsTypeahead](https://docs.bsky.app/docs/api/app-bsky-actor-search-actors-typeahead)
  - [app.bsky.actor.searchActors](https://docs.bsky.app/docs/api/app-bsky-actor-search-actors)

---

### **Feed and Content Management**
- **Feed Description and Generators:**
  - [app.bsky.feed.describeFeedGenerator](https://docs.bsky.app/docs/api/app-bsky-feed-describe-feed-generator)
  - [app.bsky.feed.getFeedGenerator](https://docs.bsky.app/docs/api/app-bsky-feed-get-feed-generator)
  - [app.bsky.feed.getFeedGenerators](https://docs.bsky.app/docs/api/app-bsky-feed-get-feed-generators)
- **Feed Content Retrieval:**
  - [app.bsky.feed.getActorFeeds](https://docs.bsky.app/docs/api/app-bsky-feed-get-actor-feeds)
  - [app.bsky.feed.getActorLikes](https://docs.bsky.app/docs/api/app-bsky-feed-get-actor-likes)
  - [app.bsky.feed.getAuthorFeed](https://docs.bsky.app/docs/api/app-bsky-feed-get-author-feed)
  - [app.bsky.feed.getFeedSkeleton](https://docs.bsky.app/docs/api/app-bsky-feed-get-feed-skeleton)
  - [app.bsky.feed.getFeed](https://docs.bsky.app/docs/api/app-bsky-feed-get-feed)
  - [app.bsky.feed.getLikes](https://docs.bsky.app/docs/api/app-bsky-feed-get-likes)
  - [app.bsky.feed.getListFeed](https://docs.bsky.app/docs/api/app-bsky-feed-get-list-feed)
  - [app.bsky.feed.getTimeline](https://docs.bsky.app/docs/api/app-bsky-feed-get-timeline)
  - [app.bsky.feed.getSuggestedFeeds](https://docs.bsky.app/docs/api/app-bsky-feed-get-suggested-feeds)
- **Post Interactions:**
  - [app.bsky.feed.getPostThread](https://docs.bsky.app/docs/api/app-bsky-feed-get-post-thread)
  - [app.bsky.feed.getPosts](https://docs.bsky.app/docs/api/app-bsky-feed-get-posts)
  - [app.bsky.feed.getQuotes](https://docs.bsky.app/docs/api/app-bsky-feed-get-quotes)
  - [app.bsky.feed.getRepostedBy](https://docs.bsky.app/docs/api/app-bsky-feed-get-reposted-by)
- **Search:**
  - [app.bsky.feed.searchPosts](https://docs.bsky.app/docs/api/app-bsky-feed-search-posts)
- **Interactions:**
  - [app.bsky.feed.sendInteractions](https://docs.bsky.app/docs/api/app-bsky-feed-send-interactions)

---

### **Graph Management**
- **Relationships and Followers:**
  - [app.bsky.graph.getActorStarterPacks](https://docs.bsky.app/docs/api/app-bsky-graph-get-actor-starter-packs)
  - [app.bsky.graph.getFollowers](https://docs.bsky.app/docs/api/app-bsky-graph-get-followers)
  - [app.bsky.graph.getFollows](https://docs.bsky.app/docs/api/app-bsky-graph-get-follows)
  - [app.bsky.graph.getKnownFollowers](https://docs.bsky.app/docs/api/app-bsky-graph-get-known-followers)
- **Lists and Mutes:**
  - [app.bsky.graph.getList](https://docs.bsky.app/docs/api/app-bsky-graph-get-list)
  - [app.bsky.graph.getLists](https://docs.bsky.app/docs/api/app-bsky-graph-get-lists)
  - [app.bsky.graph.getListBlocks](https://docs.bsky.app/docs/api/app-bsky-graph-get-list-blocks)
  - [app.bsky.graph.getListMutes](https://docs.bsky.app/docs/api/app-bsky-graph-get-list-mutes)
- **Muting:**
  - [app.bsky.graph.muteActorList](https://docs.bsky.app/docs/api/app-bsky-graph-mute-actor-list)
  - [app.bsky.graph.unmuteActorList](https://docs.bsky.app/docs/api/app-bsky-graph-unmute-actor-list)
  - [app.bsky.graph.muteActor](https://docs.bsky.app/docs/api/app-bsky-graph-mute-actor)
  - [app.bsky.graph.unmuteActor](https://docs.bsky.app/docs/api/app-bsky-graph-unmute-actor)
  - [app.bsky.graph.muteThread](https://docs.bsky.app/docs/api/app-bsky-graph-mute-thread)
  - [app.bsky.graph.unmuteThread](https://docs.bsky.app/docs/api/app-bsky-graph-unmute-thread)
- **Suggested Follows:**
  - [app.bsky.graph.getSuggestedFollowsByActor](https://docs.bsky.app/docs/api/app-bsky-graph-get-suggested-follows-by-actor)

---

### **Notifications**
- **Retrieval and Preferences:**
  - [app.bsky.notification.getUnreadCount](https://docs.bsky.app/docs/api/app-bsky-notification-get-unread-count)
  - [app.bsky.notification.listNotifications](https://docs.bsky.app/docs/api/app-bsky-notification-list-notifications)
  - [app.bsky.notification.putPreferences](https://docs.bsky.app/docs/api/app-bsky-notification-put-preferences)
- **Push Notifications:**
  - [app.bsky.notification.registerPush](https://docs.bsky.app/docs/api/app-bsky-notification-register-push)
  - [app.bsky.notification.updateSeen](https://docs.bsky.app/docs/api/app-bsky-notification-update-seen)

---

### **Video Management**
- **Video Operations:**
  - [app.bsky.video.getJobStatus](https://docs.bsky.app/docs/api/app-bsky-video-get-job-status)
  - [app.bsky.video.getUploadLimits](https://docs.bsky.app/docs/api/app-bsky-video-get-upload-limits)
  - [app.bsky.video.uploadVideo](https://docs.bsky.app/docs/api/app-bsky-video-upload-video)

---

### **Chat Management**
- **Account Operations:**
  - [chat.bsky.actor.deleteAccount](https://docs.bsky.app/docs/api/chat-bsky-actor-delete-account)
  - [chat.bsky.actor.exportAccountData](https://docs.bsky.app/docs/api/chat-bsky-actor-export-account-data)
- **Conversations:**
  - [chat.bsky.convo.getConvoForMembers](https://docs.bsky.app/docs/api/chat-bsky-convo-get-convo-for-members)
  - [chat.bsky.convo.getConvo](https://docs.bsky.app/docs/api/chat-bsky-convo-get-convo)
  - [chat.bsky.convo.getLog](https://docs.bsky.app/docs/api/chat-bsky-convo-get-log)
  - [chat.bsky.convo.getMessages](https://docs.bsky.app/docs/api/chat-bsky-convo-get-messages)
  - [chat.bsky.convo.listConvos](https://docs.bsky.app/docs/api/chat-bsky-convo-list-convos)
  - [chat.bsky.convo.muteConvo](https://docs.bsky.app/docs/api/chat-bsky-convo-mute-convo)
  - [chat.bsky.convo.unmuteConvo](https://docs.bsky.app/docs/api/chat-bsky-convo-unmute-convo)
  - [chat.bsky.convo.leaveConvo](https://docs.bsky.app/docs/api/chat-bsky-convo-leave-convo)
  - [chat.bsky.convo.updateRead](https://docs.bsky.app/docs/api/chat-bsky-convo-update-read)
- **Messages:**
  - [chat.bsky.convo.deleteMessageForSelf](https://docs.bsky.app/docs/api/chat-bsky-convo-delete-message-for-self)
  - [chat.bsky.convo.sendMessageBatch](https://docs.bsky.app/docs/api/chat-bsky-convo-send-message-batch)
  - [chat.bsky.convo.sendMessage](https://docs.bsky.app/docs/api/chat-bsky-convo-send-message)

---

### **Administrative Operations**
- **Account Management:**
  - [com.atproto.admin.deleteAccount](https://docs.bsky.app/docs/api/com-atproto-admin-delete-account)
  - [com.atproto.admin.getAccountInfo](https://docs.bsky.app/docs/api/com-atproto-admin-get-account-info)
  - [com.atproto.admin.getAccountInfos](https://docs.bsky.app/docs/api/com-atproto-admin-get-account-infos)
  - [com.atproto.admin.updateAccountEmail](https://docs.bsky.app/docs/api/com-atproto-admin-update-account-email)
  - [com.atproto.admin.updateAccountHandle](https://docs.bsky.app/docs/api/com-atproto-admin-update-account-handle)
  - [com.atproto.admin.updateAccountPassword](https://docs.bsky.app/docs/api/com-atproto-admin-update-account-password)
  - [com.atproto.admin.updateSubjectStatus](https://docs.bsky.app/docs/api/com-atproto-admin-update-subject-status)
- **Invites:**
  - [com.atproto.admin.disableAccountInvites](https://docs.bsky.app/docs/api/com-atproto-admin-disable-account-invites)
  - [com.atproto.admin.disableInviteCodes](https://docs.bsky.app/docs/api/com-atproto-admin-disable-invite-codes)
  - [com.atproto.admin.enableAccountInvites](https://docs.bsky.app/docs/api/com-atproto-admin-enable-account-invites)
  - [com.atproto.admin.getInviteCodes](https://docs.bsky.app/docs/api/com-atproto-admin-get-invite-codes)
- **Search:**
  - [com.atproto.admin.searchAccounts](https://docs.bsky.app/docs/api/com-atproto-admin-search-accounts)

---

### **Identity Management**
- **Handles and Credentials:**
  - [com.atproto.identity.getRecommendedDidCredentials](https://docs.bsky.app/docs/api/com-atproto-identity-get-recommended-did-credentials)
  - [com.atproto.identity.requestPlcOperationSignature](https://docs.bsky.app/docs/api/com-atproto-identity-request-plc-operation-signature)
  - [com.atproto.identity.resolveHandle](https://docs.bsky.app/docs/api/com-atproto-identity-resolve-handle)
  - [com.atproto.identity.signPlcOperation](https://docs.bsky.app/docs/api/com-atproto-identity-sign-plc-operation)
  - [com.atproto.identity.submitPlcOperation](https://docs.bsky.app/docs/api/com-atproto-identity-submit-plc-operation)
  - [com.atproto.identity.updateHandle](https://docs.bsky.app/docs/api/com-atproto-identity-update-handle)

---

### **Moderation**
- **Reporting and Context:**
  - [com.atproto.moderation.createReport](https://docs.bsky.app/docs/api/com-atproto-moderation-create-report)
  - [chat.bsky.moderation.getActorMetadata](https://docs.bsky.app/docs/api/chat-bsky-moderation-get-actor-metadata)
  - [chat.bsky.moderation.getMessageContext](https://docs.bsky.app/docs/api/chat-bsky-moderation-get-message-context)
  - [chat.bsky.moderation.updateActorAccess](https://docs.bsky.app/docs/api/chat-bsky-moderation-update-actor-access)

---

### **Repository and Synchronization**
- **Repo Management:**
  - [com.atproto.repo.applyWrites](https://docs.bsky.app/docs/api/com-atproto-repo-apply-writes)
  - [com.atproto.repo.createRecord](https://docs.bsky.app/docs/api/com-atproto-repo-create-record)
  - [com.atproto.repo.deleteRecord](https://docs.bsky.app/docs/api/com-atproto-repo-delete-record)
  - [com.atproto.repo.describeRepo](https://docs.bsky.app/docs/api/com-atproto-repo-describe-repo)
  - [com.atproto.repo.importRepo](https://docs.bsky.app/docs/api/com-atproto-repo-import-repo)
  - [com.atproto.repo.listMissingBlobs](https://docs.bsky.app/docs/api/com-atproto-repo-list-missing-blobs)
  - [com.atproto.repo.listRecords](https://docs.bsky.app/docs/api/com-atproto-repo-list-records)
  - [com.atproto.repo.putRecord](https://docs.bsky.app/docs/api/com-atproto-repo-put-record)
  - [com.atproto.repo.uploadBlob](https://docs.bsky.app/docs/api/com-atproto-repo-upload-blob)
- **Sync Operations:**
  - [com.atproto.sync.getBlob](https://docs.bsky.app/docs/api/com-atproto-sync-get-blob)
  - [com.atproto.sync.getBlocks](https://docs.bsky.app/docs/api/com-atproto-sync-get-blocks)
  - [com.atproto.sync.getLatestCommit](https://docs.bsky.app/docs/api/com-atproto-sync-get-latest-commit)
  - [com.atproto.sync.getRecord](https://docs.bsky.app/docs/api/com-atproto-sync-get-record)
  - [com.atproto.sync.getRepoStatus](https://docs.bsky.app/docs/api/com-atproto-sync-get-repo-status)
  - [com.atproto.sync.getRepo](https://docs.bsky.app/docs/api/com-atproto-sync-get-repo)
  - [com.atproto.sync.listBlobs](https://docs.bsky.app/docs/api/com-atproto-sync-list-blobs)
  - [com.atproto.sync.listRepos](https://docs.bsky.app/docs/api/com-atproto-sync-list-repos)
  - [com.atproto.sync.notifyOfUpdate](https://docs.bsky.app/docs/api/com-atproto-sync-notify-of-update)
  - [com.atproto.sync.requestCrawl](https://docs.bsky.app/docs/api/com-atproto-sync-request-crawl)

---

### **Tooling**
- **Communication Templates:**
  - [tools.ozone.communication.createTemplate](https://docs.bsky.app/docs/api/tools-ozone-communication-create-template)
  - [tools.ozone.communication.deleteTemplate](https://docs.bsky.app/docs/api/tools-ozone-communication-delete-template)
  - [tools.ozone.communication.listTemplates](https://docs.bsky.app/docs/api/tools-ozone-communication-list-templates)
  - [tools.ozone.communication.updateTemplate](https://docs.bsky.app/docs/api/tools-ozone-communication-update-template)
- **Moderation:**
  - [tools.ozone.moderation.emitEvent](https://docs.bsky.app/docs/api/tools-ozone-moderation-emit-event)
  - [tools.ozone.moderation.getEvent](https://docs.bsky.app/docs/api/tools-ozone-moderation-get-event)
  - [tools.ozone.moderation.getRecord](https://docs.bsky.app/docs/api/tools-ozone-moderation-get-record)
  - [tools.ozone.moderation.getRecords](https://docs.bsky.app/docs/api/tools-ozone-moderation-get-records)
  - [tools.ozone.moderation.getRepo](https://docs.bsky.app/docs/api/tools-ozone-moderation-get-repo)
  - [tools.ozone.moderation.queryEvents](https://docs.bsky.app/docs/api/tools-ozone-moderation-query-events)
  - [tools.ozone.moderation.queryStatuses](https://docs.bsky.app/docs/api/tools-ozone-moderation-query-statuses)
- **Sets:**
  - [tools.ozone.set.addValues](https://docs.bsky.app/docs/api/tools-ozone-set-add-values)
  - [tools.ozone.set.deleteSet](https://docs.bsky.app/docs/api/tools-ozone-set-delete-set)
  - [tools.ozone.set.deleteValues](https://docs.bsky.app/docs/api/tools-ozone-set-delete-values)
  - [tools.ozone.set.getValues](https://docs.bsky.app/docs/api/tools-ozone-set-get-values)
  - [tools.ozone.set.querySets](https://docs.bsky.app/docs/api/tools-ozone-set-query-sets)
  - [tools.ozone.set.upsertSet](https://docs.bsky.app/docs/api/tools-ozone-set-upsert-set)
- **Signatures:**
  - [tools.ozone.signature.findCorrelation](https://docs.bsky.app/docs/api/tools-ozone-signature-find-correlation)
  - [tools.ozone.signature.findRelatedAccounts](https://docs.bsky.app/docs/api/tools-ozone-signature-find-related-accounts)
  - [tools.ozone.signature.searchAccounts](https://docs.bsky.app/docs/api/tools-ozone-signature-search-accounts)
- **Teams:**
  - [tools.ozone.team.addMember](https://docs.bsky.app/docs/api/tools-ozone-team-add-member)
  - [tools.ozone.team.deleteMember](https://docs.bsky.app/docs/api/tools-ozone-team-delete-member)
  - [tools.ozone.team.listMembers](https://docs.bsky.app/docs/api/tools-ozone-team-list-members)
  - [tools.ozone.team.updateMember](https://docs.bsky.app/docs/api/tools-ozone-team-update-member)
