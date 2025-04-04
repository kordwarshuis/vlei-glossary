## Definition
the existence of more than one version of a Verifiable [KEL](key-event-log) for a given [AID](AID).  
Source: Dr. S.Smith, 2024

## Explanation
_Duplicity_ is used to describe external inconsistency. Publication of two or more versions of a KEL, each of which is internally consistent is duplicity. Given that signatures are non-repudiable any duplicity is detectable and provable given possession of any two mutually inconsistent versions of a KEL. In KERI [consistency](inconsistency) is is used to described data that is internally consistent and cryptographically verifiably so.

## KERI related
Duplicity means the existence of **more than one version** of a verifiable KEL for a given AID. Because every event in a KEL must be signed with non-repudiable signatures any inconsistency between any two instances of the KEL for a given AID is provable evidence of duplicity on the part of the signers with respect to either or both the key-state of that AID and/or any anchored data at a given key-state. A shorter KEL that does not differ in any of its events with respect to another but longer KEL is not duplicitous but merely incomplete. To clarify, duplicity evident means that duplicity is provable via the presentation of a set of two or more mutually inconsistent but independently verifiable instances of a KEL.
Source [Sam Smith](https://github.com/WebOfTrust/ietf-keri/blob/main/draft-ssmith-keri.md#basic-terminology)

## Outside world
In common language 'duplicity' has a slightly different connotation: 'two-facedness', 'dishonesty', 'deceitfulness', 'deviousness,'two-facedness', 'falseness'.