# ![LOGO](logo.png) Google Play Movies Partner **flow**ground Connector

## Description

A generated **flow**ground connector for the Google Play Movies Partner API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/playmoviespartner/v1/swagger.json<br/>
Generated at: 2019-05-07T17:41:50+03:00

## API Description

Gets the delivery status of titles for Google Play Movies Partners.

## Authorization

Supported authorization schemes:
- OAuth2
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Avails owned or managed by the partner.<br/>
> <br/>
> See _Authentication and Authorization rules_ and<br/>
> _List methods rules_ for more information about this method.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `title` - _optional_ - Filter that matches Avails with a `title_internal_alias`,
`series_title_internal_alias`, `season_title_internal_alias`,
or `episode_title_internal_alias` that contains the given
case-insensitive title.
* `videoIds` - _optional_ - Filter Avails that match any of the given `video_id`s.
* `pageToken` - _optional_ - See _List methods rules_ for info about this field.
* `pageSize` - _optional_ - See _List methods rules_ for info about this field.
* `altIds` - _optional_ - Filter Avails that match (case-insensitive) any of the given partner-specific custom ids.
* `pphNames` - _optional_ - See _List methods rules_ for info about this field.
* `altId` - _optional_ - Filter Avails that match a case-insensitive, partner-specific custom id.
NOTE: this field is deprecated and will be removed on V2; `alt_ids`
should be used instead.
* `studioNames` - _optional_ - See _List methods rules_ for info about this field.
* `territories` - _optional_ - Filter Avails that match (case-insensitive) any of the given country codes,
using the "ISO 3166-1 alpha-2" format (examples: "US", "us", "Us").
* `callback` - _optional_ - JSONP
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

### Get an Avail given its avail group id and avail id.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `availId` - _required_ - REQUIRED. Avail ID.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `bearer_token` - _optional_ - OAuth bearer token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `callback` - _optional_ - JSONP
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

### List Orders owned or managed by the partner.<br/>
> <br/>
> See _Authentication and Authorization rules_ and<br/>
> _List methods rules_ for more information about this method.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `pageToken` - _optional_ - See _List methods rules_ for info about this field.
* `customId` - _optional_ - Filter Orders that match a case-insensitive, partner-specific custom id.
* `videoIds` - _optional_ - Filter Orders that match any of the given `video_id`s.
* `pageSize` - _optional_ - See _List methods rules_ for info about this field.
* `pphNames` - _optional_ - See _List methods rules_ for info about this field.
* `status` - _optional_ - Filter Orders that match one of the given status.
* `name` - _optional_ - Filter that matches Orders with a `name`, `show`, `season` or `episode`
that contains the given case-insensitive name.
* `studioNames` - _optional_ - See _List methods rules_ for info about this field.
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `callback` - _optional_ - JSONP
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

### Get an Order given its id.<br/>
> <br/>
> See _Authentication and Authorization rules_ and<br/>
> _Get methods rules_ for more information about this method.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `orderId` - _required_ - REQUIRED. Order ID.
* `quotaUser` - _optional_ - Available to use for quota purposes for server-side applications. Can be any arbitrary string assigned to a user, but should not exceed 40 characters.
* `pp` - _optional_ - Pretty-print response.
* `bearer_token` - _optional_ - OAuth bearer token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `callback` - _optional_ - JSONP
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

### List StoreInfos owned or managed by the partner.<br/>
> <br/>
> See _Authentication and Authorization rules_ and<br/>
> _List methods rules_ for more information about this method.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `seasonIds` - _optional_ - Filter StoreInfos that match any of the given `season_id`s.
* `pageToken` - _optional_ - See _List methods rules_ for info about this field.
* `videoId` - _optional_ - Filter StoreInfos that match a given `video_id`.
NOTE: this field is deprecated and will be removed on V2; `video_ids`
should be used instead.
* `videoIds` - _optional_ - Filter StoreInfos that match any of the given `video_id`s.
* `pageSize` - _optional_ - See _List methods rules_ for info about this field.
* `mids` - _optional_ - Filter StoreInfos that match any of the given `mid`s.
* `pphNames` - _optional_ - See _List methods rules_ for info about this field.
* `countries` - _optional_ - Filter StoreInfos that match (case-insensitive) any of the given country
codes, using the "ISO 3166-1 alpha-2" format (examples: "US", "us", "Us").
* `name` - _optional_ - Filter that matches StoreInfos with a `name` or `show_name`
that contains the given case-insensitive name.
* `studioNames` - _optional_ - See _List methods rules_ for info about this field.
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

### Get a StoreInfo given its video id and country.<br/>
> <br/>
> See _Authentication and Authorization rules_ and<br/>
> _Get methods rules_ for more information about this method.

*Tags:* `accounts`

#### Input Parameters
* `accountId` - _required_ - REQUIRED. See _General rules_ for more information about this field.
* `videoId` - _required_ - REQUIRED. Video ID.
* `country` - _required_ - REQUIRED. Edit country.
* `pp` - _optional_ - Pretty-print response.
* `bearer_token` - _optional_ - OAuth bearer token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `upload_protocol` - _optional_ - Upload protocol for media (e.g. "raw", "multipart").
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `uploadType` - _optional_ - Legacy upload protocol for media (e.g. "media", "multipart").
* `fields` - _optional_ - Selector specifying which fields to include in a partial response.
* `callback` - _optional_ - JSONP
* `$.xgafv` - _optional_ - V1 error format.
    Possible values: 1, 2.
* `alt` - _optional_ - Data format for response.
    Possible values: json, media, proto.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-playmoviespartner-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
