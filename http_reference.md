Here is a categorized list of BlueSky endpoints based on functionality and domain.
The list helps streamline understanding and makes it easier to identify the purpose and grouping of each endpoint from the [BlueSky HTTP reference](https://docs.bsky.app/docs/category/http-reference).

---

### **Actor Management**
- **Preferences:**
  - [app.bsky.actor.getPreferences](https://docs.bsky.app/docs/api/app.bsky.actor.getPreferences)
  - [app.bsky.actor.putPreferences](https://docs.bsky.app/docs/api/app.bsky.actor.putPreferences)
- **Profiles:**
  - [app.bsky.actor.getProfile](https://docs.bsky.app/docs/api/app.bsky.actor.getProfile)
  - [app.bsky.actor.getProfiles](https://docs.bsky.app/docs/api/app.bsky.actor.getProfiles)
  - [app.bsky.actor.getSuggestions](https://docs.bsky.app/docs/api/app.bsky.actor.getSuggestions)
  - [app.bsky.actor.searchActorsTypeahead](https://docs.bsky.app/docs/api/app.bsky.actor.searchActorsTypeahead)
  - [app.bsky.actor.searchActors](https://docs.bsky.app/docs/api/app.bsky.actor.searchActors)

---

### **Feed and Content Management**
- **Feed Description and Generators:**
  - [app.bsky.feed.describeFeedGenerator](https://docs.bsky.app/docs/api/app.bsky.feed.describeFeedGenerator)
  - [app.bsky.feed.getFeedGenerator](https://docs.bsky.app/docs/api/app.bsky.feed.getFeedGenerator)
  - [app.bsky.feed.getFeedGenerators](https://docs.bsky.app/docs/api/app.bsky.feed.getFeedGenerators)
- **Feed Content Retrieval:**
  - [app.bsky.feed.getActorFeeds](https://docs.bsky.app/docs/api/app.bsky.feed.getActorFeeds)
  - [app.bsky.feed.getActorLikes](https://docs.bsky.app/docs/api/app.bsky.feed.getActorLikes)
  - [app.bsky.feed.getAuthorFeed](https://docs.bsky.app/docs/api/app.bsky.feed.getAuthorFeed)
  - [app.bsky.feed.getFeedSkeleton](https://docs.bsky.app/docs/api/app.bsky.feed.getFeedSkeleton)
  - [app.bsky.feed.getFeed](https://docs.bsky.app/docs/api/app.bsky.feed.getFeed)
  - [app.bsky.feed.getLikes](https://docs.bsky.app/docs/api/app.bsky.feed.getLikes)
  - [app.bsky.feed.getListFeed](https://docs.bsky.app/docs/api/app.bsky.feed.getListFeed)
  - [app.bsky.feed.getTimeline](https://docs.bsky.app/docs/api/app.bsky.feed.getTimeline)
  - [app.bsky.feed.getSuggestedFeeds](https://docs.bsky.app/docs/api/app.bsky.feed.getSuggestedFeeds)
- **Post Interactions:**
  - [app.bsky.feed.getPostThread](https://docs.bsky.app/docs/api/app.bsky.feed.getPostThread)
  - [app.bsky.feed.getPosts](https://docs.bsky.app/docs/api/app.bsky.feed.getPosts)
  - [app.bsky.feed.getQuotes](https://docs.bsky.app/docs/api/app.bsky.feed.getQuotes)
  - [app.bsky.feed.getRepostedBy](https://docs.bsky.app/docs/api/app.bsky.feed.getRepostedBy)
- **Search:**
  - [app.bsky.feed.searchPosts](https://docs.bsky.app/docs/api/app.bsky.feed.searchPosts)
- **Interactions:**
  - [app.bsky.feed.sendInteractions](https://docs.bsky.app/docs/api/app.bsky.feed.sendInteractions)

---

### **Graph Management**
- **Relationships and Followers:**
  - [app.bsky.graph.getActorStarterPacks](https://docs.bsky.app/docs/api/app.bsky.graph.getActorStarterPacks)
  - [app.bsky.graph.getFollowers](https://docs.bsky.app/docs/api/app.bsky.graph.getFollowers)
  - [app.bsky.graph.getFollows](https://docs.bsky.app/docs/api/app.bsky.graph.getFollows)
  - [app.bsky.graph.getKnownFollowers](https://docs.bsky.app/docs/api/app.bsky.graph.getKnownFollowers)
- **Lists and Mutes:**
  - [app.bsky.graph.getList](https://docs.bsky.app/docs/api/app.bsky.graph.getList)
  - [app.bsky.graph.getLists](https://docs.bsky.app/docs/api/app.bsky.graph.getLists)
  - [app.bsky.graph.getListBlocks](https://docs.bsky.app/docs/api/app.bsky.graph.getListBlocks)
  - [app.bsky.graph.getListMutes](https://docs.bsky.app/docs/api/app.bsky.graph.getListMutes)
- **Muting:**
  - [app.bsky.graph.muteActorList](https://docs.bsky.app/docs/api/app.bsky.graph.muteActorList)
  - [app.bsky.graph.unmuteActorList](https://docs.bsky.app/docs/api/app.bsky.graph.unmuteActorList)
  - [app.bsky.graph.muteActor](https://docs.bsky.app/docs/api/app.bsky.graph.muteActor)
  - [app.bsky.graph.unmuteActor](https://docs.bsky.app/docs/api/app.bsky.graph.unmuteActor)
  - [app.bsky.graph.muteThread](https://docs.bsky.app/docs/api/app.bsky.graph.muteThread)
  - [app.bsky.graph.unmuteThread](https://docs.bsky.app/docs/api/app.bsky.graph.unmuteThread)
- **Suggested Follows:**
  - [app.bsky.graph.getSuggestedFollowsByActor](https://docs.bsky.app/docs/api/app.bsky.graph.getSuggestedFollowsByActor)

---

### **Notifications**
- **Retrieval and Preferences:**
  - [app.bsky.notification.getUnreadCount](https://docs.bsky.app/docs/api/app.bsky.notification.getUnreadCount)
  - [app.bsky.notification.listNotifications](https://docs.bsky.app/docs/api/app.bsky.notification.listNotifications)
  - [app.bsky.notification.putPreferences](https://docs.bsky.app/docs/api/app.bsky.notification.putPreferences)
- **Push Notifications:**
  - [app.bsky.notification.registerPush](https://docs.bsky.app/docs/api/app.bsky.notification.registerPush)
  - [app.bsky.notification.updateSeen](https://docs.bsky.app/docs/api/app.bsky.notification.updateSeen)

---

### **Video Management**
- **Video Operations:**
  - [app.bsky.video.getJobStatus](https://docs.bsky.app/docs/api/app.bsky.video.getJobStatus)
  - [app.bsky.video.getUploadLimits](https://docs.bsky.app/docs/api/app.bsky.video.getUploadLimits)
  - [app.bsky.video.uploadVideo](https://docs.bsky.app/docs/api/app.bsky.video.uploadVideo)

---

### **Chat Management**
- **Account Operations:**
  - [chat.bsky.actor.deleteAccount](https://docs.bsky.app/docs/api/chat.bsky.actor.deleteAccount)
  - [chat.bsky.actor.exportAccountData](https://docs.bsky.app/docs/api/chat.bsky.actor.exportAccountData)
- **Conversations:**
  - [chat.bsky.convo.getConvoForMembers](https://docs.bsky.app/docs/api/chat.bsky.convo.getConvoForMembers)
  - [chat.bsky.convo.getConvo](https://docs.bsky.app/docs/api/chat.bsky.convo.getConvo)
  - [chat.bsky.convo.getLog](https://docs.bsky.app/docs/api/chat.bsky.convo.getLog)
  - [chat.bsky.convo.getMessages](https://docs.bsky.app/docs/api/chat.bsky.convo.getMessages)
  - [chat.bsky.convo.listConvos](https://docs.bsky.app/docs/api/chat.bsky.convo.listConvos)
  - [chat.bsky.convo.muteConvo](https://docs.bsky.app/docs/api/chat.bsky.convo.muteConvo)
  - [chat.bsky.convo.unmuteConvo](https://docs.bsky.app/docs/api/chat.bsky.convo.unmuteConvo)
  - [chat.bsky.convo.leaveConvo](https://docs.bsky.app/docs/api/chat.bsky.convo.leaveConvo)
  - [chat.bsky.convo.updateRead](https://docs.bsky.app/docs/api/chat.bsky.convo.updateRead)
- **Messages:**
  - [chat.bsky.convo.deleteMessageForSelf](https://docs.bsky.app/docs/api/chat.bsky.convo.deleteMessageForSelf)
  - [chat.bsky.convo.sendMessageBatch](https://docs.bsky.app/docs/api/chat.bsky.convo.sendMessageBatch)
  - [chat.bsky.convo.sendMessage](https://docs.bsky.app/docs/api/chat.bsky.convo.sendMessage)

---

### **Administrative Operations**
- **Account Management:**
  - [com.atproto.admin.deleteAccount](https://docs.bsky.app/docs/api/com.atproto.admin.deleteAccount)
  - [com.atproto.admin.getAccountInfo](https://docs.bsky.app/docs/api/com.atproto.admin.getAccountInfo)
  - [com.atproto.admin.getAccountInfos](https://docs.bsky.app/docs/api/com.atproto.admin.getAccountInfos)
  - [com.atproto.admin.updateAccountEmail](https://docs.bsky.app/docs/api/com.atproto.admin.updateAccountEmail)
  - [com.atproto.admin.updateAccountHandle](https://docs.bsky.app/docs/api/com.atproto.admin.updateAccountHandle)
  - [com.atproto.admin.updateAccountPassword](https://docs.bsky.app/docs/api/com.atproto.admin.updateAccountPassword)
  - [com.atproto.admin.updateSubjectStatus](https://docs.bsky.app/docs/api/com.atproto.admin.updateSubjectStatus)
- **Invites:**
  - [com.atproto.admin.disableAccountInvites](https://docs.bsky.app/docs/api/com.atproto.admin.disableAccountInvites)
  - [com.atproto.admin.disableInviteCodes](https://docs.bsky.app/docs/api/com.atproto.admin.disableInviteCodes)
  - [com.atproto.admin.enableAccountInvites](https://docs.bsky.app/docs/api/com.atproto.admin.enableAccountInvites)
  - [com.atproto.admin.getInviteCodes](https://docs.bsky.app/docs/api/com.atproto.admin.getInviteCodes)
- **Search:**
  - [com.atproto.admin.searchAccounts](https://docs.bsky.app/docs/api/com.atproto.admin.searchAccounts)

---

### **Identity Management**
- **Handles and Credentials:**
  - [com.atproto.identity.getRecommendedDidCredentials](https://docs.bsky.app/docs/api/com.atproto.identity.getRecommendedDidCredentials)
  - [com.atproto.identity.requestPlcOperationSignature](https://docs.bsky.app/docs/api/com.atproto.identity.requestPlcOperationSignature)
  - [com.atproto.identity.resolveHandle](https://docs.bsky.app/docs/api/com.atproto.identity.resolveHandle)
  - [com.atproto.identity.signPlcOperation](https://docs.bsky.app/docs/api/com.atproto.identity.signPlcOperation)
  - [com.atproto.identity.submitPlcOperation](https://docs.bsky.app/docs/api/com.atproto.identity.submitPlcOperation)
  - [com.atproto.identity.updateHandle](https://docs.bsky.app/docs/api/com.atproto.identity.updateHandle)

---

### **Moderation**
- **Reporting and Context:**
  - [com.atproto.moderation.createReport](https://docs.bsky.app/docs/api/com.atproto.moderation.createReport)
  - [chat.bsky.moderation.getActorMetadata](https://docs.bsky.app/docs/api/chat.bsky.moderation.getActorMetadata)
  - [chat.bsky.moderation.getMessageContext](https://docs.bsky.app/docs/api/chat.bsky.moderation.getMessageContext)
  - [chat.bsky.moderation.updateActorAccess](https://docs.bsky.app/docs/api/chat.bsky.moderation.updateActorAccess)

---

### **Repository and Synchronization**
- **Repo Management:**
  - [com.atproto.repo.applyWrites](https://docs.bsky.app/docs/api/com.atproto.repo.applyWrites)
  - [com.atproto.repo.createRecord](https://docs.bsky.app/docs/api/com.atproto.repo.createRecord)
  - [com.atproto.repo.deleteRecord](https://docs.bsky.app/docs/api/com.atproto.repo.deleteRecord)
  - [com.atproto.repo.describeRepo](https://docs.bsky.app/docs/api/com.atproto.repo.describeRepo)
  - [com.atproto.repo.importRepo](https://docs.bsky.app/docs/api/com.atproto.repo.importRepo)
  - [com.atproto.repo.listMissingBlobs](https://docs.bsky.app/docs/api/com.atproto.repo.listMissingBlobs)
  - [com.atproto.repo.listRecords](https://docs.bsky.app/docs/api/com.atproto.repo.listRecords)
  - [com.atproto.repo.putRecord](https://docs.bsky.app/docs/api/com.atproto.repo.putRecord)
  - [com.atproto.repo.uploadBlob](https://docs.bsky.app/docs/api/com.atproto.repo.uploadBlob)
- **Sync Operations:**
  - [com.atproto.sync.getBlob](https://docs.bsky.app/docs/api/com.atproto.sync.getBlob)
  - [com.atproto.sync.getBlocks](https://docs.bsky.app/docs/api/com.atproto.sync.getBlocks)
  - [com.atproto.sync.getLatestCommit](https://docs.bsky.app/docs/api/com.atproto.sync.getLatestCommit)
  - [com.atproto.sync.getRecord](https://docs.bsky.app/docs/api/com.atproto.sync.getRecord)
  - [com.atproto.sync.getRepoStatus](https://docs.bsky.app/docs/api/com.atproto.sync.getRepoStatus)
  - [com.atproto.sync.getRepo](https://docs.bsky.app/docs/api/com.atproto.sync.getRepo)
  - [com.atproto.sync.listBlobs](https://docs.bsky.app/docs/api/com.atproto.sync.listBlobs)
  - [com.atproto.sync.listRepos](https://docs.bsky.app/docs/api/com.atproto.sync.listRepos)
  - [com.atproto.sync.notifyOfUpdate](https://docs.bsky.app/docs/api/com.atproto.sync.notifyOfUpdate)
  - [com.atproto.sync.requestCrawl](https://docs.bsky.app/docs/api/com.atproto.sync.requestCrawl)

---

### **Tooling**
- **Communication Templates:**
  - [tools.ozone.communication.createTemplate](https://docs.bsky.app/docs/api/tools.ozone.communication.createTemplate)
  - [tools.ozone.communication.deleteTemplate](https://docs.bsky.app/docs/api/tools.ozone.communication.deleteTemplate)
  - [tools.ozone.communication.listTemplates](https://docs.bsky.app/docs/api/tools.ozone.communication.listTemplates)
  - [tools.ozone.communication.updateTemplate](https://docs.bsky.app/docs/api/tools.ozone.communication.updateTemplate)
- **Moderation:**
  - [tools.ozone.moderation.emitEvent](https://docs.bsky.app/docs/api/tools.ozone.moderation.emitEvent)
  - [tools.ozone.moderation.getEvent](https://docs.bsky.app/docs/api/tools.ozone.moderation.getEvent)
  - [tools.ozone.moderation.getRecord](https://docs.bsky.app/docs/api/tools.ozone.moderation.getRecord)
  - [tools.ozone.moderation.getRecords](https://docs.bsky.app/docs/api/tools.ozone.moderation.getRecords)
  - [tools.ozone.moderation.getRepo](https://docs.bsky.app/docs/api/tools.ozone.moderation.getRepo)
  - [tools.ozone.moderation.queryEvents](https://docs.bsky.app/docs/api/tools.ozone.moderation.queryEvents)
  - [tools.ozone.moderation.queryStatuses](https://docs.bsky.app/docs/api/tools.ozone.moderation.queryStatuses)
- **Sets:**
  - [tools.ozone.set.addValues](https://docs.bsky.app/docs/api/tools.ozone.set.addValues)
  - [tools.ozone.set.deleteSet](https://docs.bsky.app/docs/api/tools.ozone.set.deleteSet)
  - [tools.ozone.set.deleteValues](https://docs.bsky.app/docs/api/tools.ozone.set.deleteValues)
  - [tools.ozone.set.getValues](https://docs.bsky.app/docs/api/tools.ozone.set.getValues)
  - [tools.ozone.set.querySets](https://docs.bsky.app/docs/api/tools.ozone.set.querySets)
  - [tools.ozone.set.upsertSet](https://docs.bsky.app/docs/api/tools.ozone.set.upsertSet)
- **Signatures:**
  - [tools.ozone.signature.findCorrelation](https://docs.bsky.app/docs/api/tools.ozone.signature.findCorrelation)
  - [tools.ozone.signature.findRelatedAccounts](https://docs.bsky.app/docs/api/tools.ozone.signature.findRelatedAccounts)
  - [tools.ozone.signature.searchAccounts](https://docs.bsky.app/docs/api/tools.ozone.signature.searchAccounts)
- **Teams:**
  - [tools.ozone.team.addMember](https://docs.bsky.app/docs/api/tools.ozone.team.addMember)
  - [tools.ozone.team.deleteMember](https://docs.bsky.app/docs/api/tools.ozone.team.deleteMember)
  - [tools.ozone.team.listMembers](https://docs.bsky.app/docs/api/tools.ozone.team.listMembers)
  - [tools.ozone.team.updateMember](https://docs.bsky.app/docs/api/tools.ozone.team.updateMember)
