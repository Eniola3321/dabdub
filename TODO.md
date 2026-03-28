# Profile Module Implementation TODO

Approved plan breakdown into logical steps. Mark [x] as completed.

## 1. Database Migration [x]

- Manual migration created: 1769990000000-AddUserProfileFields.ts
- \`npm run migration:run\` running

## 2. Update User Entity [x]

- Added bio, avatarKey, twitterHandle, instagramHandle
- Removed duplicate columns

## 3. Create Profile DTOs [x]

- ✓ all 4 DTOs

## 4. Create Profile Service [x]

- ✓ profile.service.ts
- ✓ profile.service.spec.ts

## 5. Create Profile Controller [x]

- ✓ profile.controller.ts

## 6. Create Profile Module [x]

- ✓ profile.module.ts

## 7. Update Existing Files [ ]

- Extend users/dto/update-profile.dto.ts (align with new)
- Extend users.service.ts update() for new fields
- Align users/dto/user-response.dto.ts with ProfileDto
- app.module.ts: import ProfileModule
- uploads: add AVATAR purpose (optional, reusing MERCHANT_LOGO)

## 8. R2 Public Avatar URLs [ ]

- Placeholder public URL in service (upgrade to presign later)

## 9. Testing [ ]

- Run \`cd backend && npm test profile\`
- Manual endpoints

## 10. Completion [ ]
