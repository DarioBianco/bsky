Here is a categorized list of BlueSky endpoints based on functionality and domain.
The list helps streamline understanding and makes it easier to identify the purpose and grouping of each endpoint from the [BlueSky HTTP reference](https://docs.bsky.app/docs/category/http-reference).

---

### **Actor Management**
- **Preferences:**
  - `app.bsky.actor.getPreferences`
  - `app.bsky.actor.putPreferences`
- **Profiles:**
  - `app.bsky.actor.getProfile`
  - `app.bsky.actor.getProfiles`
  - `app.bsky.actor.getSuggestions`
  - `app.bsky.actor.searchActorsTypeahead`
  - `app.bsky.actor.searchActors`

---

### **Feed and Content Management**
- **Feed Description and Generators:**
  - `app.bsky.feed.describeFeedGenerator`
  - `app.bsky.feed.getFeedGenerator`
  - `app.bsky.feed.getFeedGenerators`
- **Feed Content Retrieval:**
  - `app.bsky.feed.getActorFeeds`
  - `app.bsky.feed.getActorLikes`
  - `app.bsky.feed.getAuthorFeed`
  - `app.bsky.feed.getFeedSkeleton`
  - `app.bsky.feed.getFeed`
  - `app.bsky.feed.getLikes`
  - `app.bsky.feed.getListFeed`
  - `app.bsky.feed.getTimeline`
  - `app.bsky.feed.getSuggestedFeeds`
- **Post Interactions:**
  - `app.bsky.feed.getPostThread`
  - `app.bsky.feed.getPosts`
  - `app.bsky.feed.getQuotes`
  - `app.bsky.feed.getRepostedBy`
- **Search:**
  - `app.bsky.feed.searchPosts`
- **Interactions:**
  - `app.bsky.feed.sendInteractions`

---

### **Graph Management**
- **Relationships and Followers:**
  - `app.bsky.graph.getActorStarterPacks`
  - `app.bsky.graph.getFollowers`
  - `app.bsky.graph.getFollows`
  - `app.bsky.graph.getKnownFollowers`
- **Lists and Mutes:**
  - `app.bsky.graph.getList`
  - `app.bsky.graph.getLists`
  - `app.bsky.graph.getListBlocks`
  - `app.bsky.graph.getListMutes`
- **Muting:**
  - `app.bsky.graph.muteActorList`
  - `app.bsky.graph.unmuteActorList`
  - `app.bsky.graph.muteActor`
  - `app.bsky.graph.unmuteActor`
  - `app.bsky.graph.muteThread`
  - `app.bsky.graph.unmuteThread`
- **Suggested Follows:**
  - `app.bsky.graph.getSuggestedFollowsByActor`

---

### **Notifications**
- **Retrieval and Preferences:**
  - `app.bsky.notification.getUnreadCount`
  - `app.bsky.notification.listNotifications`
  - `app.bsky.notification.putPreferences`
- **Push Notifications:**
  - `app.bsky.notification.registerPush`
  - `app.bsky.notification.updateSeen`

---

### **Video Management**
- **Video Operations:**
  - `app.bsky.video.getJobStatus`
  - `app.bsky.video.getUploadLimits`
  - `app.bsky.video.uploadVideo`

---

### **Chat Management**
- **Account Operations:**
  - `chat.bsky.actor.deleteAccount`
  - `chat.bsky.actor.exportAccountData`
- **Conversations:**
  - `chat.bsky.convo.getConvoForMembers`
  - `chat.bsky.convo.getConvo`
  - `chat.bsky.convo.getLog`
  - `chat.bsky.convo.getMessages`
  - `chat.bsky.convo.listConvos`
  - `chat.bsky.convo.muteConvo`
  - `chat.bsky.convo.unmuteConvo`
  - `chat.bsky.convo.leaveConvo`
  - `chat.bsky.convo.updateRead`
- **Messages:**
  - `chat.bsky.convo.deleteMessageForSelf`
  - `chat.bsky.convo.sendMessageBatch`
  - `chat.bsky.convo.sendMessage`

---

### **Administrative Operations**
- **Account Management:**
  - `com.atproto.admin.deleteAccount`
  - `com.atproto.admin.getAccountInfo`
  - `com.atproto.admin.getAccountInfos`
  - `com.atproto.admin.updateAccountEmail`
  - `com.atproto.admin.updateAccountHandle`
  - `com.atproto.admin.updateAccountPassword`
  - `com.atproto.admin.updateSubjectStatus`
- **Invites:**
  - `com.atproto.admin.disableAccountInvites`
  - `com.atproto.admin.disableInviteCodes`
  - `com.atproto.admin.enableAccountInvites`
  - `com.atproto.admin.getInviteCodes`
- **Search:**
  - `com.atproto.admin.searchAccounts`

---

### **Identity Management**
- **Handles and Credentials:**
  - `com.atproto.identity.getRecommendedDidCredentials`
  - `com.atproto.identity.requestPlcOperationSignature`
  - `com.atproto.identity.resolveHandle`
  - `com.atproto.identity.signPlcOperation`
  - `com.atproto.identity.submitPlcOperation`
  - `com.atproto.identity.updateHandle`

---

### **Moderation**
- **Reporting and Context:**
  - `com.atproto.moderation.createReport`
  - `chat.bsky.moderation.getActorMetadata`
  - `chat.bsky.moderation.getMessageContext`
  - `chat.bsky.moderation.updateActorAccess`

---

### **Repository and Synchronization**
- **Repo Management:**
  - `com.atproto.repo.applyWrites`
  - `com.atproto.repo.createRecord`
  - `com.atproto.repo.deleteRecord`
  - `com.atproto.repo.describeRepo`
  - `com.atproto.repo.importRepo`
  - `com.atproto.repo.listMissingBlobs`
  - `com.atproto.repo.listRecords`
  - `com.atproto.repo.putRecord`
  - `com.atproto.repo.uploadBlob`
- **Sync Operations:**
  - `com.atproto.sync.getBlob`
  - `com.atproto.sync.getBlocks`
  - `com.atproto.sync.getLatestCommit`
  - `com.atproto.sync.getRecord`
  - `com.atproto.sync.getRepoStatus`
  - `com.atproto.sync.getRepo`
  - `com.atproto.sync.listBlobs`
  - `com.atproto.sync.listRepos`
  - `com.atproto.sync.notifyOfUpdate`
  - `com.atproto.sync.requestCrawl`

---

### **Tooling**
- **Communication Templates:**
  - `tools.ozone.communication.createTemplate`
  - `tools.ozone.communication.deleteTemplate`
  - `tools.ozone.communication.listTemplates`
  - `tools.ozone.communication.updateTemplate`
- **Moderation:**
  - `tools.ozone.moderation.emitEvent`
  - `tools.ozone.moderation.getEvent`
  - `tools.ozone.moderation.getRecord`
  - `tools.ozone.moderation.getRecords`
  - `tools.ozone.moderation.getRepo`
  - `tools.ozone.moderation.queryEvents`
  - `tools.ozone.moderation.queryStatuses`
- **Sets:**
  - `tools.ozone.set.addValues`
  - `tools.ozone.set.deleteSet`
  - `tools.ozone.set.deleteValues`
  - `tools.ozone.set.getValues`
  - `tools.ozone.set.querySets`
  - `tools.ozone.set.upsertSet`
- **Signatures:**
  - `tools.ozone.signature.findCorrelation`
  - `tools.ozone.signature.findRelatedAccounts`
  - `tools.ozone.signature.searchAccounts`
- **Teams:**
  - `tools.ozone.team.addMember`
  - `tools.ozone.team.deleteMember`
  - `tools.ozone.team.listMembers`
  - `tools.ozone.team.updateMember`
