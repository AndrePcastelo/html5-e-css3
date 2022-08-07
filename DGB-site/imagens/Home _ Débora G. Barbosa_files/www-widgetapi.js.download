(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=ca(this);function r(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
r("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.i=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.i};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
r("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function t(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=t(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ja(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ka="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ja(d,e)&&(a[e]=d[e])}return a};
r("Object.assign",function(a){return a||ka});
var la="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ma;
if("function"==typeof Object.setPrototypeOf)ma=Object.setPrototypeOf;else{var na;a:{var oa={a:!0},pa={};try{pa.__proto__=oa;na=pa.a;break a}catch(a){}na=!1}ma=na?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ra=ma;
function u(a,b){a.prototype=la(b.prototype);a.prototype.constructor=a;if(ra)ra(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.O=b.prototype}
function ta(){this.A=!1;this.m=null;this.j=void 0;this.i=1;this.s=this.u=0;this.J=this.l=null}
function ua(a){if(a.A)throw new TypeError("Generator is already running");a.A=!0}
ta.prototype.H=function(a){this.j=a};
function va(a,b){a.l={Na:b,Sa:!0};a.i=a.u||a.s}
ta.prototype.return=function(a){this.l={return:a};this.i=this.s};
function w(a,b,c){a.i=c;return{value:b}}
ta.prototype.v=function(a){this.i=a};
function xa(a,b,c){a.u=b;void 0!=c&&(a.s=c)}
function ya(a,b){a.i=b;a.u=0}
function za(a){a.u=0;var b=a.l.Na;a.l=null;return b}
function Aa(a){a.J=[a.l];a.u=0;a.s=0}
function Ba(a){var b=a.J.splice(0)[0];(b=a.l=a.l||b)?b.Sa?a.i=a.u||a.s:void 0!=b.v&&a.s<b.v?(a.i=b.v,a.l=null):a.i=a.s:a.i=0}
function Ca(a){this.i=new ta;this.j=a}
function Da(a,b){ua(a.i);var c=a.i.m;if(c)return Ea(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.i.return);
a.i.return(b);return Fa(a)}
function Ea(a,b,c,d){try{var e=b.call(a.i.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.i.A=!1,e;var f=e.value}catch(g){return a.i.m=null,va(a.i,g),Fa(a)}a.i.m=null;d.call(a.i,f);return Fa(a)}
function Fa(a){for(;a.i.i;)try{var b=a.j(a.i);if(b)return a.i.A=!1,{value:b.value,done:!1}}catch(c){a.i.j=void 0,va(a.i,c)}a.i.A=!1;if(a.i.l){b=a.i.l;a.i.l=null;if(b.Sa)throw b.Na;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ga(a){this.next=function(b){ua(a.i);a.i.m?b=Ea(a,a.i.m.next,b,a.i.H):(a.i.H(b),b=Fa(a));return b};
this.throw=function(b){ua(a.i);a.i.m?b=Ea(a,a.i.m["throw"],b,a.i.H):(va(a.i,b),b=Fa(a));return b};
this.return=function(b){return Da(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ha(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ha(new Ga(new Ca(a)))}
function Ia(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
r("Reflect.setPrototypeOf",function(a){return a?a:ra?function(b,c){try{return ra(b,c),!0}catch(d){return!1}}:null});
r("Promise",function(a){function b(g){this.i=0;this.l=void 0;this.j=[];this.A=!1;var h=this.m();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.i=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.j=function(g){if(null==this.i){this.i=[];var h=this;this.l(function(){h.s()})}this.i.push(g)};
var e=fa.setTimeout;c.prototype.l=function(g){e(g,0)};
c.prototype.s=function(){for(;this.i&&this.i.length;){var g=this.i;this.i=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.m(l)}}}this.i=null};
c.prototype.m=function(g){this.l(function(){throw g;})};
b.prototype.m=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.cb),reject:g(this.s)}};
b.prototype.cb=function(g){if(g===this)this.s(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.fb(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.bb(g):this.u(g)}};
b.prototype.bb=function(g){var h=void 0;try{h=g.then}catch(k){this.s(k);return}"function"==typeof h?this.gb(h,g):this.u(g)};
b.prototype.s=function(g){this.H(2,g)};
b.prototype.u=function(g){this.H(1,g)};
b.prototype.H=function(g,h){if(0!=this.i)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.i);this.i=g;this.l=h;2===this.i&&this.eb();this.J()};
b.prototype.eb=function(){var g=this;e(function(){if(g.da()){var h=fa.console;"undefined"!==typeof h&&h.error(g.l)}},1)};
b.prototype.da=function(){if(this.A)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.l;return k(g)};
b.prototype.J=function(){if(null!=this.j){for(var g=0;g<this.j.length;++g)f.j(this.j[g]);this.j=null}};
var f=new c;b.prototype.fb=function(g){var h=this.m();g.qa(h.resolve,h.reject)};
b.prototype.gb=function(g,h){var k=this.m();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(v,p){return"function"==typeof v?function(y){try{l(v(y))}catch(z){m(z)}}:p}
var l,m,q=new b(function(v,p){l=v;m=p});
this.qa(k(g,l),k(h,m));return q};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.qa=function(g,h){function k(){switch(l.i){case 1:g(l.l);break;case 2:h(l.l);break;default:throw Error("Unexpected state: "+l.i);}}
var l=this;null==this.j?f.j(k):this.j.push(k);this.A=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=t(g),m=l.next();!m.done;m=l.next())d(m.value).qa(h,k)})};
b.all=function(g){var h=t(g),k=h.next();return k.done?d([]):new b(function(l,m){function q(y){return function(z){v[y]=z;p--;0==p&&l(v)}}
var v=[],p=0;do v.push(void 0),p++,d(k.value).qa(q(v.length-1),m),k=h.next();while(!k.done)})};
return b});
r("WeakMap",function(a){function b(k){this.i=(h+=Math.random()+1).toString();if(k){k=t(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!ja(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m.delete(k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(q){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ja(k,g))throw Error("WeakMap key fail: "+k);k[g][this.i]=l;return this};
b.prototype.get=function(k){return d(k)&&ja(k,g)?k[g][this.i]:void 0};
b.prototype.has=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)};
b.prototype.delete=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)?delete k[g][this.i]:!1};
return b});
r("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.i;return ha(function(){if(l){for(;l.head!=h.i;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.data_[l];if(m&&ja(h.data_,l))for(h=0;h<m.length;h++){var q=m[h];if(k!==k&&q.key!==q.key||k===q.key)return{id:l,list:m,index:h,entry:q}}return{id:l,list:m,index:-1,entry:void 0}}
function e(h){this.data_={};this.i=b();this.size=0;if(h){h=t(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(t([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(q){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.i,previous:this.i.previous,head:this.i,key:h,value:k},l.list.push(l.entry),this.i.previous.next=l.entry,this.i.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.i=this.i.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ja(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
r("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
r("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
r("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ja(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
r("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
r("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
r("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function Ka(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
r("Array.prototype.entries",function(a){return a?a:function(){return Ka(this,function(b,c){return[b,c]})}});
r("Array.prototype.keys",function(a){return a?a:function(){return Ka(this,function(b){return b})}});
r("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
r("Object.setPrototypeOf",function(a){return a||ra});
r("Set",function(a){function b(c){this.i=new Map;if(c){c=t(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.i.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(t([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.i.set(c,c);this.size=this.i.size;return this};
b.prototype.delete=function(c){c=this.i.delete(c);this.size=this.i.size;return c};
b.prototype.clear=function(){this.i.clear();this.size=0};
b.prototype.has=function(c){return this.i.has(c)};
b.prototype.entries=function(){return this.i.entries()};
b.prototype.values=function(){return this.i.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.i.forEach(function(f){return c.call(d,f,f,e)})};
return b});
r("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push([d,b[d]]);return c}});
r("Array.prototype.values",function(a){return a?a:function(){return Ka(this,function(b,c){return c})}});
r("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
r("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
r("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
r("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ja(this,b,"includes").indexOf(b,c||0)}});
var A=this||self;function B(a,b){a=a.split(".");b=b||A;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function La(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ma(a){var b=La(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Pa(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Qa(a){return Object.prototype.hasOwnProperty.call(a,Ra)&&a[Ra]||(a[Ra]=++Sa)}
var Ra="closure_uid_"+(1E9*Math.random()>>>0),Sa=0;function Ta(a,b,c){return a.call.apply(a.bind,arguments)}
function Ua(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Va(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Va=Ta:Va=Ua;return Va.apply(null,arguments)}
function C(a,b){a=a.split(".");var c=A;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function Wa(a,b){function c(){}
c.prototype=b.prototype;a.O=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Qb=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Xa(a){return a}
;function Za(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Za);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Wa(Za,Error);Za.prototype.name="CustomError";function $a(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.l=!b&&/[?&]ae=1(&|$)/.test(a);this.m=!b&&/[?&]ae=2(&|$)/.test(a);if((this.i=/[?&]adurl=([^&]*)/.exec(a))&&this.i[1]){try{var c=decodeURIComponent(this.i[1])}catch(d){c=null}this.j=c}}
;function ab(){}
function bb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var cb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},D=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},db=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
D(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d},eb=Array.prototype.every?function(a,b){return Array.prototype.every.call(a,b,void 0)}:function(a,b){for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&!b.call(void 0,d[e],e,a))return!1;
return!0};
function fb(a,b){b=cb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function gb(a){return Array.prototype.concat.apply([],arguments)}
function hb(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function ib(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ma(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function jb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function kb(a){var b=mb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function nb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function ob(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=ob(a[c]);return b}
var pb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function qb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<pb.length;f++)c=pb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var rb;function xb(){}
function yb(a){return new xb(zb,a)}
var zb={};yb("");var Ab=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},Bb=/&/g,Cb=/</g,Db=/>/g,Eb=/"/g,Fb=/'/g,Gb=/\x00/g,Hb=/[\x00&<>"']/;function Ib(a,b){this.i=b===Jb?a:""}
Ib.prototype.toString=function(){return this.i.toString()};
var Jb={},Kb=new Ib("about:invalid#zClosurez",Jb);function Lb(){var a=A.navigator;return a&&(a=a.userAgent)?a:""}
function E(a){return-1!=Lb().indexOf(a)}
;function Mb(){return(E("Chrome")||E("CriOS"))&&!E("Edge")||E("Silk")}
;var Nb={};function Ob(a){this.i=Nb===Nb?a:""}
Ob.prototype.toString=function(){return this.i.toString()};var Pb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Qb(a){return a?decodeURI(a):a}
function Rb(a){return Qb(a.match(Pb)[3]||null)}
function Sb(a){var b=a.match(Pb);a=b[1];var c=b[2],d=b[3];b=b[4];var e="";a&&(e+=a+":");d&&(e+="//",c&&(e+=c+"@"),e+=d,b&&(e+=":"+b));return e}
function Tb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Tb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Ub(a){var b=[],c;for(c in a)Tb(c,a[c],b);return b.join("&")}
var Zb=/#|$/;function $b(a,b){var c=a.search(Zb);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.slice(d,-1!==e?e:0).replace(/\+/g," "))}
;var ac={};function bc(a){if(a!==ac)throw Error("requires a valid immutable API token");}
;function cc(){return E("iPhone")&&!E("iPod")&&!E("iPad")}
;function dc(a){dc[" "](a);return a}
dc[" "]=function(){};var ec=E("Opera"),fc=E("Trident")||E("MSIE"),gc=E("Edge"),hc=E("Gecko")&&!(-1!=Lb().toLowerCase().indexOf("webkit")&&!E("Edge"))&&!(E("Trident")||E("MSIE"))&&!E("Edge"),ic=-1!=Lb().toLowerCase().indexOf("webkit")&&!E("Edge");function jc(){var a=A.document;return a?a.documentMode:void 0}
var kc;a:{var lc="",mc=function(){var a=Lb();if(hc)return/rv:([^\);]+)(\)|;)/.exec(a);if(gc)return/Edge\/([\d\.]+)/.exec(a);if(fc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(ic)return/WebKit\/(\S+)/.exec(a);if(ec)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
mc&&(lc=mc?mc[1]:"");if(fc){var nc=jc();if(null!=nc&&nc>parseFloat(lc)){kc=String(nc);break a}}kc=lc}var oc=kc,pc;if(A.document&&fc){var qc=jc();pc=qc?qc:parseInt(oc,10)||void 0}else pc=void 0;var rc=pc;var sc=cc()||E("iPod"),uc=E("iPad");!E("Android")||Mb();Mb();var vc=E("Safari")&&!(Mb()||E("Coast")||E("Opera")||E("Edge")||E("Edg/")||E("OPR")||E("Firefox")||E("FxiOS")||E("Silk")||E("Android"))&&!(cc()||E("iPad")||E("iPod"));var wc={},xc=null;
function yc(a,b){Ma(a);void 0===b&&(b=0);if(!xc){xc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));wc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===xc[h]&&(xc[h]=g)}}}b=wc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var zc="undefined"!==typeof Uint8Array,Ac={};var Bc;function Cc(a){if(Ac!==Ac)throw Error("illegal external caller");this.Ia=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
Cc.prototype.isEmpty=function(){return null==this.Ia};var Dc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function Ec(a,b){Object.isFrozen(a)||(Dc?a[Dc]|=b:void 0!==a.M?a.M|=b:Object.defineProperties(a,{M:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function Fc(a,b){Object.isExtensible(a)&&(Dc?a[Dc]&&(a[Dc]&=~b):void 0!==a.M&&(a.M&=~b))}
function Gc(a){var b;Dc?b=a[Dc]:b=a.M;return null==b?0:b}
function Hc(a,b){Dc?a[Dc]=b:void 0!==a.M?a.M=b:Object.defineProperties(a,{M:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function Lc(a){Ec(a,1);return a}
function F(a){return a?!!(Gc(a)&2):!1}
function Mc(a){Ec(a,16);return a}
function Nc(a){if(!Array.isArray(a))throw Error("cannot mark non-array as shared mutably");Fc(a,16)}
function Oc(a,b){b?Ec(a,8):Fc(a,8)}
function Pc(a,b){Hc(b,(Gc(a)|0)&-51)}
;function Qc(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Rc,Sc=Object.freeze(Lc([]));function Tc(a){if(F(a.o))throw Error("Cannot mutate an immutable Message");}
var Uc="undefined"!=typeof Symbol&&"undefined"!=typeof Symbol.hasInstance;function Vc(a){return{value:a,configurable:!1,writable:!1,enumerable:!1}}
;function Wc(a){return a.displayName||a.name||"unknown type name"}
function Xc(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Wc(b)+" but got "+(a&&Wc(a.constructor)));return a}
function Yc(a,b,c,d){c=void 0===c?!1:c;d=void 0===d?!1:d;if(Array.isArray(a))return new b(d?Mc(a):a);if(c)return new b}
;function Zc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(zc&&null!=a&&a instanceof Uint8Array)return yc(a);if(a instanceof Cc){var b=a.Ia;null!=b&&"string"!==typeof b&&(zc&&b instanceof Uint8Array?b=yc(b):(La(b),b=null));return null==b?"":a.Ia=b}}}return a}
;function $c(a,b,c){if(null!=a){if(Array.isArray(a))a=ad(a,b,c);else if(Qc(a)){var d={},e;for(e in a)d[e]=$c(a[e],b,c);a=d}else a=b(a);return a}}
function ad(a,b,c){var d=Array.prototype.slice.call(a);c(a,d);for(a=0;a<d.length;a++)d[a]=$c(d[a],b,c);return d}
function bd(a){if(a&&"object"==typeof a&&a.toJSON)return a.toJSON();a=Zc(a);return Array.isArray(a)?ad(a,bd,cd):a}
function dd(a){if("object"===typeof a){if(zc&&null!=a&&a instanceof Uint8Array)return new Uint8Array(a);if(Array.isArray(a.o)&&a.constructor!==Object)return a.clone()}return a}
function cd(){}
;function ed(a){return a.j||(a.j=a.o[a.l+a.T]={})}
function fd(a,b,c){return-1===b?null:b>=a.l?a.j?a.j[b]:void 0:(void 0===c?0:c)&&a.j&&(c=a.j[b],null!=c)?c:a.o[b+a.T]}
function H(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||Tc(a);if(b>=a.l||d)return ed(a)[b]=c,a;void 0!==a.j&&a.l>=a.o.length?(d=a.o.length-1,e=b+a.T,e>=d?(a.o[d]=void 0,a.o[e]=c,a.o.push(a.j)):a.o[e]=c):a.o[b+a.T]=c;void 0!==a.j&&b in a.j&&delete a.j[b];return a}
function gd(a,b,c,d){var e=fd(a,b,d);Array.isArray(e)?e&&Gc(e)&1||Lc(e):e=Sc;if(F(a.o))c&1||(Ec(e,2),Object.freeze(e));else if(e===Sc||F(e))e=Lc(Array.prototype.slice.call(e)),H(a,b,e,d);return e}
function hd(a,b,c,d){Tc(a);(c=id(a,c))&&c!==b&&null!=d&&(a.i&&c in a.i&&(a.i[c]=void 0),H(a,c));return H(a,b,d)}
function id(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=fd(a,e)&&(0!==c&&H(a,c,void 0,!1,!0),c=e)}return c}
function jd(a,b,c,d){d=void 0===d?!1:d;var e=d;a.i||(a.i={});var f=a.i[c];if(f)b=f;else if(b=Yc(fd(a,c,e),b))a.i[c]=b,Ec(b.o,Gc(a.o)&-33);if(null==b)return b;F(b.o)&&!F(a.o)&&(b=b.Ha(),H(a,c,b.o,d),a.i[c]=b);return b}
function kd(a,b,c,d,e){e=void 0===e?!0:e;a.i||(a.i={});var f=a.i[c];d=gd(a,c,2,d);var g=!!(Gc(a.o)&16),h=F(d);h=F(a.o)||h;if(!f){f=[];for(var k=h,l=0;l<d.length;l++){var m=d[l];k=k||F(m);m=Yc(m,b,!1,g);void 0!==m&&(f.push(m),h&&Ec(m.o,2))}a.i[c]=f;Oc(d,!k)}b=h||e;e=F(f);b&&!e&&(Object.isFrozen(f)&&(a.i[c]=f=f.slice()),Ec(f,2),Object.freeze(f));!b&&e&&(a.i[c]=f=f.slice());return f}
function I(a,b,c,d){Tc(a);a.i||(a.i={});null==d?b=d=void 0:b=Xc(d,b).o;a.i[c]=d;return H(a,c,b)}
function ld(a,b,c,d,e){Tc(a);a.i||(a.i={});null!=e?b=Xc(e,b).o:b=e=void 0;a.i[c]=e;hd(a,c,d,b)}
function md(a,b,c,d){Tc(a);if(null!=d){var e=Lc([]);for(var f=!1,g=0;g<d.length;g++)e[g]=Xc(d[g],b).o,f=f||F(e[g]);a.i||(a.i={});a.i[c]=d;Oc(e,!f)}else a.i&&(a.i[c]=void 0),e=Sc;return H(a,c,e)}
function nd(a,b,c,d){Tc(a);var e=kd(a,c,b,void 0,!1);c=null!=d?Xc(d,c):new c;a=gd(a,b,2);e.push(c);a.push(c.o);bc(ac);F(c.o)&&Oc(a,!1)}
function od(a,b){a=fd(a,b);return null==a?"":a}
;function pd(a,b,c){a||(a=qd);qd=null;var d=this.constructor.i||0,e=0<d,f=this.constructor.j;a?Gc(a)&16&&Ec(a,32):(a=f?[f]:[],Ec(a,48));e&&0<a.length&&Qc(a[a.length-1])&&"g"in a[a.length-1]&&(d=0);this.T=(f?0:-1)-d;this.i=void 0;this.o=a;a:{f=this.o.length;d=f-1;if(f&&(f=this.o[d],Qc(f))){this.j=f;b=Object.keys(f);0<b.length&&eb(b,isNaN)?this.l=Number.MAX_VALUE:this.l=d-this.T;break a}void 0!==b&&-1<b?(this.l=Math.max(b,d+1-this.T),this.j=void 0):this.l=Number.MAX_VALUE}if(!e&&this.j&&"g"in this.j)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');
if(c)for(e=0;e<c.length;e++)b=c[e],b<this.l?(b+=this.T,(d=this.o[b])?Array.isArray(d)&&Lc(d):this.o[b]=Sc):(d=ed(this),(f=d[b])?Array.isArray(f)&&Lc(f):d[b]=Sc)}
pd.prototype.toJSON=function(){var a=this.o;return Rc?a:ad(a,bd,cd)};
function rd(a){Rc=!0;try{return JSON.stringify(a.toJSON(),sd)}finally{Rc=!1}}
pd.prototype.clone=function(){var a=ad(this.o,dd,Pc);Mc(a);qd=a;a=new this.constructor(a);qd=null;td(a,this);return a};
pd.prototype.isMutable=function(a){bc(a);return!F(this.o)};
pd.prototype.toString=function(){return this.o.toString()};
function sd(a,b){return Zc(b)}
function td(a,b){b.ha&&(a.ha=b.ha.slice());var c=b.i;if(c){b=b.j;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length){var h=a,k=f;k=void 0===k?!1:k;f=F(h.o);var l=kd(h,e[0].constructor,g,k,f);g=gd(h,g,0,void 0===k?!1:k);if(!(h=f)&&(h=g)){if(!g)throw Error("cannot check mutability state of non-array");h=!(Gc(g)&8)}if(h){for(h=0;h<l.length;h++)(k=l[h])&&F(k.o)&&!f&&(l[h]=l[h].Ha(),g[h]=l[h].o);Oc(g,!0)}f=l;for(l=0;l<Math.min(f.length,e.length);l++)td(f[l],e[l])}}else(f=
jd(a,e.constructor,g,f))&&td(f,e)}}}}
var qd;function ud(){pd.apply(this,arguments)}
u(ud,pd);ud.prototype.Ha=function(){return this};
if(Uc){var vd={};Object.defineProperties(ud,(vd[Symbol.hasInstance]=Vc(function(){throw Error("Cannot perform instanceof checks for MutableMessage");}),vd))};function wd(a,b,c,d,e,f){(a=a.i&&a.i[c])?Array.isArray(a)?(e=f.za?Lc(a.slice()):a,md(b,0<e.length?e[0].constructor:void 0,c,e)):I(b,a.constructor,c,a):(zc&&d instanceof Uint8Array?e=d.length?new Cc(new Uint8Array(d)):Bc||(Bc=new Cc(null)):(Array.isArray(d)&&(e?Ec(d,2):d&&Gc(d)&1&&f.za?(e=d.slice(),Hc(e,(Gc(d)|0)&-51),d=e):Nc(d)),e=d),H(b,c,e))}
;function J(){ud.apply(this,arguments)}
u(J,ud);J.prototype.Ha=function(){if(F(this.o)){var a={za:!0};var b=F(this.o);if(b&&!a.za)throw Error("copyRepeatedFields must be true for frozen messages");b||Nc(this.o);var c=new this.constructor;this.ha&&(c.ha=this.ha.slice());for(var d=this.o,e=0;e<d.length;e++){var f=d[e];if(e===d.length-1&&Qc(f))for(var g in f){var h=+g;Number.isNaN(h)?ed(c)[g]=f[g]:wd(this,c,h,f[g],b,a)}else wd(this,c,e-this.T,f,b,a)}a=c}else a=this;return a};
if(Uc){var xd={};Object.defineProperties(J,(xd[Symbol.hasInstance]=Vc(Object[Symbol.hasInstance]),xd))};var yd=window;yb("csi.gstatic.com");yb("googleads.g.doubleclick.net");yb("partner.googleadservices.com");yb("pubads.g.doubleclick.net");yb("securepubads.g.doubleclick.net");yb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var zd;try{new URL("s://g"),zd=!0}catch(a){zd=!1}var Ad=zd;function Bd(a,b){a.removeAttribute("srcdoc");if(b instanceof Ib)b instanceof Ib&&b.constructor===Ib?b=b.i:(La(b),b="type_error:SafeUrl");else{a:if(Ad){try{var c=new URL(b)}catch(d){c="https:";break a}c=c.protocol}else b:{c=document.createElement("a");try{c.href=b}catch(d){c=void 0;break b}c=-1!==[":",""].indexOf(c.protocol)?"https:":c.protocol}b="javascript:"===c?"about:invalid":b}a.src=b;for(b="allow-same-origin allow-scripts allow-forms allow-popups allow-popups-to-escape-sandbox allow-storage-access-by-user-activation".split(" ");0<
a.sandbox.length;)a.sandbox.remove(a.sandbox.item(0));for(c=0;c<b.length;c++)a.sandbox.supports&&!a.sandbox.supports(b[c])||a.sandbox.add(b[c])}
;function Cd(a,b){this.width=a;this.height=b}
n=Cd.prototype;n.clone=function(){return new Cd(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.isEmpty=function(){return!(this.width*this.height)};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Dd(){var a=document;var b="IFRAME";"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Ed(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Fd(a){var b=Gd;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function Hd(){var a=[];Fd(function(b){a.push(b)});
return a}
var Gd={yb:"allow-forms",zb:"allow-modals",Ab:"allow-orientation-lock",Bb:"allow-pointer-lock",Cb:"allow-popups",Db:"allow-popups-to-escape-sandbox",Eb:"allow-presentation",Fb:"allow-same-origin",Gb:"allow-scripts",Hb:"allow-top-navigation",Ib:"allow-top-navigation-by-user-activation"},Id=bb(function(){return Hd()});
function Jd(){var a=Kd(),b={};D(Id(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Kd(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Ld(a){this.isValid=a}
function Md(a){return new Ld(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Nd=[Md("data"),Md("http"),Md("https"),Md("mailto"),Md("ftp"),new Ld(function(a){return/^[^:]*([/?#]|$)/.test(a)})];
function Od(a,b){b=void 0===b?Nd:b;for(var c=0;c<b.length;++c){var d=b[c];if(d instanceof Ld&&d.isValid(a))return new Ib(a,Jb)}}
function Pd(a){var b=void 0===b?Nd:b;return Od(a,b)||Kb}
;var Qd=(new Date).getTime();function Td(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;var Ud="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(Ud);function Vd(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(q){for(var v=g,p=0;64>p;p+=4)v[p/4]=q[p]<<24|q[p+1]<<16|q[p+2]<<8|q[p+3];for(p=16;80>p;p++)q=v[p-3]^v[p-8]^v[p-14]^v[p-16],v[p]=(q<<1|q>>>31)&4294967295;q=e[0];var y=e[1],z=e[2],G=e[3],K=e[4];for(p=0;80>p;p++){if(40>p)if(20>p){var M=G^y&(z^G);var O=1518500249}else M=y^z^G,O=1859775393;else 60>p?(M=y&z|G&(y|z),O=2400959708):(M=y^z^G,O=3395469782);M=((q<<5|q>>>27)&4294967295)+M+K+O+v[p]&4294967295;K=G;G=z;z=(y<<30|y>>>2)&4294967295;y=q;q=M}e[0]=e[0]+q&4294967295;e[1]=e[1]+y&4294967295;e[2]=
e[2]+z&4294967295;e[3]=e[3]+G&4294967295;e[4]=e[4]+K&4294967295}
function c(q,v){if("string"===typeof q){q=unescape(encodeURIComponent(q));for(var p=[],y=0,z=q.length;y<z;++y)p.push(q.charCodeAt(y));q=p}v||(v=q.length);p=0;if(0==l)for(;p+64<v;)b(q.slice(p,p+64)),p+=64,m+=64;for(;p<v;)if(f[l++]=q[p++],m++,64==l)for(l=0,b(f);p+64<v;)b(q.slice(p,p+64)),p+=64,m+=64}
function d(){var q=[],v=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var p=63;56<=p;p--)f[p]=v&255,v>>>=8;b(f);for(p=v=0;5>p;p++)for(var y=24;0<=y;y-=8)q[v++]=e[p]>>y&255;return q}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,jb:function(){for(var q=d(),v="",p=0;p<q.length;p++)v+="0123456789ABCDEF".charAt(Math.floor(q[p]/16))+"0123456789ABCDEF".charAt(q[p]%16);return v}}}
;function Wd(a,b,c){var d=String(A.location.href);return d&&a&&b?[b,Xd(Td(d),a,c||null)].join(" "):null}
function Xd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],D(d,function(h){e.push(h)}),Yd(e.join(" "));
var f=[],g=[];D(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];D(d,function(h){e.push(h)});
a=Yd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function Yd(a){var b=Vd();b.update(a);return b.jb().toLowerCase()}
;var Zd={};function $d(a){this.i=a||{cookie:""}}
n=$d.prototype;n.isEnabled=function(){if(!A.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Ba:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
n.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Ub;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Ba}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.i.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
n.get=function(a,b){for(var c=a+"=",d=(this.i.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Ab(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Ba:0,path:b,domain:c});return d};
n.isEmpty=function(){return!this.i.cookie};
n.clear=function(){for(var a=(this.i.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=Ab(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var ae=new $d("undefined"==typeof document?null:document);function be(a){return!!Zd.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function ce(a,b,c,d){(a=A[a])||(a=(new $d(document)).get(b));return a?Wd(a,c,d):null}
function de(a){var b=void 0===b?!1:b;var c=Td(String(A.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=A.__SAPISID||A.__APISID||A.__3PSAPISID||A.__OVERRIDE_SID;be(e)&&(f=f||A.__1PSAPISID);if(f)e=!0;else{var g=new $d(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID");be(e)&&(f=f||g.get("__Secure-1PAPISID"));e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?A.__SAPISID:A.__APISID,e||(e=new $d(document),
e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?Wd(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&be(b)&&((b=ce("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=ce("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;function ee(){this.l=this.l;this.s=this.s}
ee.prototype.l=!1;ee.prototype.dispose=function(){this.l||(this.l=!0,this.ga())};
ee.prototype.ga=function(){if(this.s)for(;this.s.length;)this.s.shift()()};function fe(a,b){this.type=a;this.i=this.target=b;this.defaultPrevented=this.l=!1}
fe.prototype.stopPropagation=function(){this.l=!0};
fe.prototype.preventDefault=function(){this.defaultPrevented=!0};function ge(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||A.$googDebugFname||b}catch(g){e="Not available",c=!0}b=he(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,ie[c])c=ie[c];else{c=String(c);if(!ie[c]){var f=/function\s+([^\(]+)/m.exec(c);ie[c]=f?f[1]:"[Anonymous]"}c=ie[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function he(a,b){b||(b={});b[je(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[je(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=he(a,b));return c}
function je(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var ie={};var ke=function(){if(!A.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{A.addEventListener("test",function(){},b),A.removeEventListener("test",function(){},b)}catch(c){}return a}();function le(a,b){fe.call(this,a?a.type:"");this.relatedTarget=this.i=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.j=null;a&&this.init(a,b)}
Wa(le,fe);var me={2:"touch",3:"pen",4:"mouse"};
le.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.i=b;if(b=a.relatedTarget){if(hc){a:{try{dc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:me[a.pointerType]||"";this.state=a.state;
this.j=a;a.defaultPrevented&&le.O.preventDefault.call(this)};
le.prototype.stopPropagation=function(){le.O.stopPropagation.call(this);this.j.stopPropagation?this.j.stopPropagation():this.j.cancelBubble=!0};
le.prototype.preventDefault=function(){le.O.preventDefault.call(this);var a=this.j;a.preventDefault?a.preventDefault():a.returnValue=!1};var ne="closure_listenable_"+(1E6*Math.random()|0);var oe=0;function pe(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ta=e;this.key=++oe;this.ja=this.pa=!1}
function qe(a){a.ja=!0;a.listener=null;a.proxy=null;a.src=null;a.ta=null}
;function re(a){this.src=a;this.listeners={};this.i=0}
re.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.i++);var g=se(a,b,d,e);-1<g?(b=a[g],c||(b.pa=!1)):(b=new pe(b,this.src,f,!!d,e),b.pa=c,a.push(b));return b};
re.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=se(e,b,c,d);return-1<b?(qe(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.i--),!0):!1};
function te(a,b){var c=b.type;c in a.listeners&&fb(a.listeners[c],b)&&(qe(b),0==a.listeners[c].length&&(delete a.listeners[c],a.i--))}
function se(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.ja&&f.listener==b&&f.capture==!!c&&f.ta==d)return e}return-1}
;var ue="closure_lm_"+(1E6*Math.random()|0),ve={},we=0;function xe(a,b,c,d,e){if(d&&d.once)ye(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)xe(a,b[f],c,d,e);else c=ze(c),a&&a[ne]?a.X(b,c,Pa(d)?!!d.capture:!!d,e):Ae(a,b,c,!1,d,e)}
function Ae(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Pa(e)?!!e.capture:!!e,h=Be(a);h||(a[ue]=h=new re(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ce();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)ke||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(De(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");we++}}
function Ce(){function a(c){return b.call(a.src,a.listener,c)}
var b=Ee;return a}
function ye(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)ye(a,b[f],c,d,e);else c=ze(c),a&&a[ne]?a.i.add(String(b),c,!0,Pa(d)?!!d.capture:!!d,e):Ae(a,b,c,!0,d,e)}
function Fe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Fe(a,b[f],c,d,e);else(d=Pa(d)?!!d.capture:!!d,c=ze(c),a&&a[ne])?a.i.remove(String(b),c,d,e):a&&(a=Be(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=se(b,c,d,e)),(c=-1<a?b[a]:null)&&Ge(c))}
function Ge(a){if("number"!==typeof a&&a&&!a.ja){var b=a.src;if(b&&b[ne])te(b.i,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(De(c),d):b.addListener&&b.removeListener&&b.removeListener(d);we--;(c=Be(b))?(te(c,a),0==c.i&&(c.src=null,b[ue]=null)):qe(a)}}}
function De(a){return a in ve?ve[a]:ve[a]="on"+a}
function Ee(a,b){if(a.ja)a=!0;else{b=new le(b,this);var c=a.listener,d=a.ta||a.src;a.pa&&Ge(a);a=c.call(d,b)}return a}
function Be(a){a=a[ue];return a instanceof re?a:null}
var He="__closure_events_fn_"+(1E9*Math.random()>>>0);function ze(a){if("function"===typeof a)return a;a[He]||(a[He]=function(b){return a.handleEvent(b)});
return a[He]}
;function Ie(){ee.call(this);this.i=new re(this);this.da=this;this.H=null}
Wa(Ie,ee);Ie.prototype[ne]=!0;Ie.prototype.addEventListener=function(a,b,c,d){xe(this,a,b,c,d)};
Ie.prototype.removeEventListener=function(a,b,c,d){Fe(this,a,b,c,d)};
function Je(a,b){var c=a.H;if(c){var d=[];for(var e=1;c;c=c.H)d.push(c),++e}a=a.da;c=b.type||b;"string"===typeof b?b=new fe(b,a):b instanceof fe?b.target=b.target||a:(e=b,b=new fe(c,a),qb(b,e));e=!0;if(d)for(var f=d.length-1;!b.l&&0<=f;f--){var g=b.i=d[f];e=Ke(g,c,!0,b)&&e}b.l||(g=b.i=a,e=Ke(g,c,!0,b)&&e,b.l||(e=Ke(g,c,!1,b)&&e));if(d)for(f=0;!b.l&&f<d.length;f++)g=b.i=d[f],e=Ke(g,c,!1,b)&&e}
Ie.prototype.ga=function(){Ie.O.ga.call(this);if(this.i){var a=this.i,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,qe(d[e]);delete a.listeners[c];a.i--}}this.H=null};
Ie.prototype.X=function(a,b,c,d){return this.i.add(String(a),b,!1,c,d)};
function Ke(a,b,c,d){b=a.i.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.ja&&g.capture==c){var h=g.listener,k=g.ta||g.src;g.pa&&te(a.i,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Le(a){Ie.call(this);var b=this;this.J=this.m=0;this.K=null!=a?a:{P:function(e,f){return setTimeout(e,f)},
Z:function(e){clearTimeout(e)}};
var c,d;this.j=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.u=function(){return x(function(e){return w(e,Me(b),0)})};
window.addEventListener("offline",this.u);window.addEventListener("online",this.u);this.J||Ne(this)}
u(Le,Ie);function Oe(){var a=Pe;Le.i||(Le.i=new Le(a));return Le.i}
Le.prototype.dispose=function(){window.removeEventListener("offline",this.u);window.removeEventListener("online",this.u);this.K.Z(this.J);delete Le.i};
Le.prototype.F=function(){return this.j};
function Ne(a){a.J=a.K.P(function(){var b;return x(function(c){if(1==c.i)return a.j?(null==(b=window.navigator)?0:b.onLine)?c.v(3):w(c,Me(a),3):w(c,Me(a),3);Ne(a);c.i=0})},3E4)}
function Me(a,b){return a.A?a.A:a.A=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.i){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,xa(h,2,3),d&&(a.m=a.K.P(function(){d.abort()},b||2E4)),w(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Aa(h);a.A=void 0;a.m&&(a.K.Z(a.m),a.m=0);g!==a.j&&(a.j=g,a.j?Je(a,"networkstatus-online"):Je(a,"networkstatus-offline"));c(g);Ba(h);break;case 2:za(h),g=!1,h.v(3)}})})}
;function Qe(){this.data_=[];this.i=-1}
Qe.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.i=-1)};
Qe.prototype.get=function(a){return!!this.data_[a]};
function Re(a){-1===a.i&&(a.i=db(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function Se(a){J.call(this,a,-1,Te)}
u(Se,J);function Ue(a,b){return H(a,2,b)}
function Ve(a,b){return H(a,3,b)}
function We(a,b){return H(a,4,b)}
function Xe(a,b){return H(a,5,b)}
function Ye(a,b){return H(a,9,b)}
function Ze(a,b){return md(a,$e,10,b)}
function af(a,b){return H(a,11,b)}
function bf(a,b){return H(a,1,b)}
function cf(a,b){return H(a,7,b)}
function $e(a){J.call(this,a)}
u($e,J);var Te=[10,6];var df="platform platformVersion architecture model uaFullVersion bitness fullVersionList wow64".split(" ");function ef(a){var b;return null!=(b=a.google_tag_data)?b:a.google_tag_data={}}
function ff(){var a=window,b,c;if("function"!==typeof(null==(b=a.navigator)?void 0:null==(c=b.userAgentData)?void 0:c.getHighEntropyValues))return null;var d=ef(a);if(d.uach_promise)return d.uach_promise;a=a.navigator.userAgentData.getHighEntropyValues(df).then(function(e){null!=d.uach||(d.uach=e);return e});
return d.uach_promise=a}
function gf(a){var b;return af(Ze(Xe(Ue(bf(We(cf(Ye(Ve(new Se,a.architecture||""),a.bitness||""),a.mobile||!1),a.model||""),a.platform||""),a.platformVersion||""),a.uaFullVersion||""),(null==(b=a.fullVersionList)?void 0:b.map(function(c){var d=new $e;d=H(d,1,c.brand);return H(d,2,c.version)}))||[]),a.wow64||!1)}
function hf(){var a,b;return null!=(b=null==(a=ff())?void 0:a.then(function(c){return gf(c)}))?b:null}
;function jf(a,b){this.l=a;this.m=b;this.j=0;this.i=null}
jf.prototype.get=function(){if(0<this.j){this.j--;var a=this.i;this.i=a.next;a.next=null}else a=this.l();return a};
function kf(a,b){a.m(b);100>a.j&&(a.j++,b.next=a.i,a.i=b)}
;var lf;function mf(){var a=A.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!E("Presto")&&(a=function(){var e=Dd();e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Va(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!E("Trident")&&!E("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.La;c.La=null;e()}};
return function(e){d.next={La:e};d=d.next;b.port2.postMessage(0)}}return function(e){A.setTimeout(e,0)}}
;function nf(a){A.setTimeout(function(){throw a;},0)}
;function of(){this.j=this.i=null}
of.prototype.add=function(a,b){var c=pf.get();c.set(a,b);this.j?this.j.next=c:this.i=c;this.j=c};
of.prototype.remove=function(){var a=null;this.i&&(a=this.i,this.i=this.i.next,this.i||(this.j=null),a.next=null);return a};
var pf=new jf(function(){return new qf},function(a){return a.reset()});
function qf(){this.next=this.scope=this.i=null}
qf.prototype.set=function(a,b){this.i=a;this.scope=b;this.next=null};
qf.prototype.reset=function(){this.next=this.scope=this.i=null};var rf,sf=!1,tf=new of;function uf(a,b){rf||vf();sf||(rf(),sf=!0);tf.add(a,b)}
function vf(){if(A.Promise&&A.Promise.resolve){var a=A.Promise.resolve(void 0);rf=function(){a.then(wf)}}else rf=function(){var b=wf;
"function"!==typeof A.setImmediate||A.Window&&A.Window.prototype&&!E("Edge")&&A.Window.prototype.setImmediate==A.setImmediate?(lf||(lf=mf()),lf(b)):A.setImmediate(b)}}
function wf(){for(var a;a=tf.remove();){try{a.i.call(a.scope)}catch(b){nf(b)}kf(pf,a)}sf=!1}
;function xf(a,b){this.i=a[A.Symbol.iterator]();this.j=b}
xf.prototype[Symbol.iterator]=function(){return this};
xf.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value),done:a.done}};
function yf(a,b){return new xf(a,b)}
;function zf(){this.blockSize=-1}
;function Af(){this.blockSize=-1;this.blockSize=64;this.i=[];this.s=[];this.u=[];this.l=[];this.l[0]=128;for(var a=1;a<this.blockSize;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
Wa(Af,zf);Af.prototype.reset=function(){this.i[0]=1732584193;this.i[1]=4023233417;this.i[2]=2562383102;this.i[3]=271733878;this.i[4]=3285377520;this.m=this.j=0};
function Bf(a,b,c){c||(c=0);var d=a.u;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.i[0];c=a.i[1];var g=a.i[2],h=a.i[3],k=a.i[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.i[0]=a.i[0]+b&4294967295;a.i[1]=a.i[1]+c&4294967295;a.i[2]=a.i[2]+g&4294967295;a.i[3]=a.i[3]+h&4294967295;a.i[4]=a.i[4]+k&4294967295}
Af.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.s,f=this.j;d<b;){if(0==f)for(;d<=c;)Bf(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Bf(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Bf(this,e);f=0;break}}this.j=f;this.m+=b}};
Af.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.blockSize-(this.j-56));for(var c=this.blockSize-1;56<=c;c--)this.s[c]=b&255,b/=256;Bf(this,this.s);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.i[c]>>d&255,++b;return a};function Cf(){}
Cf.prototype.next=function(){return Df};
var Df={done:!0,value:void 0};function Ef(a){return{value:a,done:!1}}
Cf.prototype.L=function(){return this};function Ff(a){if(a instanceof Gf||a instanceof Hf||a instanceof If)return a;if("function"==typeof a.next)return new Gf(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Gf(function(){return a[Symbol.iterator]()});
if("function"==typeof a.L)return new Gf(function(){return a.L()});
throw Error("Not an iterator or iterable.");}
function Gf(a){this.j=a}
Gf.prototype.L=function(){return new Hf(this.j())};
Gf.prototype[Symbol.iterator]=function(){return new If(this.j())};
Gf.prototype.i=function(){return new If(this.j())};
function Hf(a){this.j=a}
u(Hf,Cf);Hf.prototype.next=function(){return this.j.next()};
Hf.prototype[Symbol.iterator]=function(){return new If(this.j)};
Hf.prototype.i=function(){return new If(this.j)};
function If(a){Gf.call(this,function(){return a});
this.l=a}
u(If,Gf);If.prototype.next=function(){return this.l.next()};function Jf(a,b){this.j={};this.i=[];this.l=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Jf)for(c=Kf(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Kf(a){hg(a);return a.i.concat()}
n=Jf.prototype;n.has=function(a){return ig(this.j,a)};
n.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||jg;hg(this);for(var c,d=0;c=this.i[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function jg(a,b){return a===b}
n.isEmpty=function(){return 0==this.size};
n.clear=function(){this.j={};this.l=this.size=this.i.length=0};
n.remove=function(a){return this.delete(a)};
n.delete=function(a){return ig(this.j,a)?(delete this.j[a],--this.size,this.l++,this.i.length>2*this.size&&hg(this),!0):!1};
function hg(a){if(a.size!=a.i.length){for(var b=0,c=0;b<a.i.length;){var d=a.i[b];ig(a.j,d)&&(a.i[c++]=d);b++}a.i.length=c}if(a.size!=a.i.length){var e={};for(c=b=0;b<a.i.length;)d=a.i[b],ig(e,d)||(a.i[c++]=d,e[d]=1),b++;a.i.length=c}}
n.get=function(a,b){return ig(this.j,a)?this.j[a]:b};
n.set=function(a,b){ig(this.j,a)||(this.size+=1,this.i.push(a),this.l++);this.j[a]=b};
n.forEach=function(a,b){for(var c=Kf(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
n.clone=function(){return new Jf(this)};
n.keys=function(){return Ff(this.L(!0)).i()};
n.values=function(){return Ff(this.L(!1)).i()};
n.entries=function(){var a=this;return yf(this.keys(),function(b){return[b,a.get(b)]})};
n.L=function(a){hg(this);var b=0,c=this.l,d=this,e=new Cf;e.next=function(){if(c!=d.l)throw Error("The map has changed since the iterator was created");if(b>=d.i.length)return Df;var f=d.i[b++];return Ef(a?f:d.j[f])};
return e};
function ig(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;var kg=A.JSON.stringify;function lg(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function mg(a){this.i=0;this.A=void 0;this.m=this.j=this.l=null;this.s=this.u=!1;if(a!=ab)try{var b=this;a.call(void 0,function(c){ng(b,2,c)},function(c){ng(b,3,c)})}catch(c){ng(this,3,c)}}
function og(){this.next=this.context=this.onRejected=this.j=this.i=null;this.l=!1}
og.prototype.reset=function(){this.context=this.onRejected=this.j=this.i=null;this.l=!1};
var pg=new jf(function(){return new og},function(a){a.reset()});
function qg(a,b,c){var d=pg.get();d.j=a;d.onRejected=b;d.context=c;return d}
mg.prototype.then=function(a,b,c){return rg(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
mg.prototype.$goog_Thenable=!0;mg.prototype.cancel=function(a){if(0==this.i){var b=new sg(a);uf(function(){tg(this,b)},this)}};
function tg(a,b){if(0==a.i)if(a.l){var c=a.l;if(c.j){for(var d=0,e=null,f=null,g=c.j;g&&(g.l||(d++,g.i==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.i&&1==d?tg(c,b):(f?(d=f,d.next==c.m&&(c.m=d),d.next=d.next.next):ug(c),vg(c,e,3,b)))}a.l=null}else ng(a,3,b)}
function wg(a,b){a.j||2!=a.i&&3!=a.i||xg(a);a.m?a.m.next=b:a.j=b;a.m=b}
function rg(a,b,c,d){var e=qg(null,null,null);e.i=new mg(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof sg?g(h):f(k)}catch(l){g(l)}}:g});
e.i.l=a;wg(a,e);return e.i}
mg.prototype.J=function(a){this.i=0;ng(this,2,a)};
mg.prototype.da=function(a){this.i=0;ng(this,3,a)};
function ng(a,b,c){if(0==a.i){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.i=1;a:{var d=c,e=a.J,f=a.da;if(d instanceof mg){wg(d,qg(e||ab,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Pa(d))try{var k=d.then;if("function"===typeof k){yg(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.A=c,a.i=b,a.l=null,xg(a),3!=b||c instanceof sg||zg(a,c))}}
function yg(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function xg(a){a.u||(a.u=!0,uf(a.H,a))}
function ug(a){var b=null;a.j&&(b=a.j,a.j=b.next,b.next=null);a.j||(a.m=null);return b}
mg.prototype.H=function(){for(var a;a=ug(this);)vg(this,a,this.i,this.A);this.u=!1};
function vg(a,b,c,d){if(3==c&&b.onRejected&&!b.l)for(;a&&a.s;a=a.l)a.s=!1;if(b.i)b.i.l=null,Ag(b,c,d);else try{b.l?b.j.call(b.context):Ag(b,c,d)}catch(e){Bg.call(null,e)}kf(pg,b)}
function Ag(a,b,c){2==b?a.j.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function zg(a,b){a.s=!0;uf(function(){a.s&&Bg.call(null,b)})}
var Bg=nf;function sg(a){Za.call(this,a)}
Wa(sg,Za);sg.prototype.name="cancel";function L(a){ee.call(this);this.A=1;this.m=[];this.u=0;this.i=[];this.j={};this.H=!!a}
Wa(L,ee);n=L.prototype;n.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.A;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.A=e+3;d.push(e);return e};
function Cg(a,b,c){var d=Dg;if(a=d.j[a]){var e=d.i;(a=a.find(function(f){return e[f+1]==b&&e[f+2]==c}))&&d.na(a)}}
n.na=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.u?(this.m.push(a),this.i[a+1]=function(){}):(c&&fb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
n.ca=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.H)for(e=0;e<c.length;e++){var g=c[e];Eg(this.i[g+1],this.i[g+2],d)}else{this.u++;try{for(e=0,f=c.length;e<f&&!this.l;e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.u--,0<this.m.length&&0==this.u)for(;c=this.m.pop();)this.na(c)}}return 0!=e}return!1};
function Eg(a,b,c){uf(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.na,this),delete this.j[a])}else this.i.length=0,this.j={}};
n.ga=function(){L.O.ga.call(this);this.clear();this.m.length=0};function Fg(a){this.i=a}
Fg.prototype.set=function(a,b){void 0===b?this.i.remove(a):this.i.set(a,kg(b))};
Fg.prototype.get=function(a){try{var b=this.i.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Fg.prototype.remove=function(a){this.i.remove(a)};function Gg(a){this.i=a}
Wa(Gg,Fg);function Hg(a){this.data=a}
function Ig(a){return void 0===a||a instanceof Hg?a:new Hg(a)}
Gg.prototype.set=function(a,b){Gg.O.set.call(this,a,Ig(b))};
Gg.prototype.j=function(a){a=Gg.O.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Gg.prototype.get=function(a){if(a=this.j(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Jg(a){this.i=a}
Wa(Jg,Gg);Jg.prototype.set=function(a,b,c){if(b=Ig(b)){if(c){if(c<Date.now()){Jg.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Jg.O.set.call(this,a,b)};
Jg.prototype.j=function(a){var b=Jg.O.j.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Jg.prototype.remove.call(this,a);else return b}};function Kg(){}
;function Lg(){}
Wa(Lg,Kg);Lg.prototype[Symbol.iterator]=function(){return Ff(this.L(!0)).i()};
Lg.prototype.clear=function(){var a=Array.from(this);a=t(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Mg(a){this.i=a}
Wa(Mg,Lg);n=Mg.prototype;n.isAvailable=function(){if(!this.i)return!1;try{return this.i.setItem("__sak","1"),this.i.removeItem("__sak"),!0}catch(a){return!1}};
n.set=function(a,b){try{this.i.setItem(a,b)}catch(c){if(0==this.i.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){a=this.i.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.i.removeItem(a)};
n.L=function(a){var b=0,c=this.i,d=new Cf;d.next=function(){if(b>=c.length)return Df;var e=c.key(b++);if(a)return Ef(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Ef(e)};
return d};
n.clear=function(){this.i.clear()};
n.key=function(a){return this.i.key(a)};function Ng(){var a=null;try{a=window.localStorage||null}catch(b){}this.i=a}
Wa(Ng,Mg);function Og(a,b){this.j=a;this.i=null;var c;if(c=fc)c=!(9<=Number(rc));if(c){Pg||(Pg=new Jf);this.i=Pg.get(a);this.i||(b?this.i=document.getElementById(b):(this.i=document.createElement("userdata"),this.i.addBehavior("#default#userData"),document.body.appendChild(this.i)),Pg.set(a,this.i));try{this.i.load(this.j)}catch(d){this.i=null}}}
Wa(Og,Lg);var Qg={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Pg=null;function Rg(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Qg[b]})}
n=Og.prototype;n.isAvailable=function(){return!!this.i};
n.set=function(a,b){this.i.setAttribute(Rg(a),b);Sg(this)};
n.get=function(a){a=this.i.getAttribute(Rg(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.i.removeAttribute(Rg(a));Sg(this)};
n.L=function(a){var b=0,c=this.i.XMLDocument.documentElement.attributes,d=new Cf;d.next=function(){if(b>=c.length)return Df;var e=c[b++];if(a)return Ef(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Ef(e)};
return d};
n.clear=function(){for(var a=this.i.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Sg(this)};
function Sg(a){try{a.i.save(a.j)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Tg(a,b){this.j=a;this.i=b+"::"}
Wa(Tg,Lg);Tg.prototype.set=function(a,b){this.j.set(this.i+a,b)};
Tg.prototype.get=function(a){return this.j.get(this.i+a)};
Tg.prototype.remove=function(a){this.j.remove(this.i+a)};
Tg.prototype.L=function(a){var b=this.j[Symbol.iterator](),c=this,d=new Cf;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.i.length)!=c.i;){e=b.next();if(e.done)return e;e=e.value}return Ef(a?e.slice(c.i.length):c.j.get(e))};
return d};function Ug(a){J.call(this,a)}
u(Ug,J);Ug.prototype.getKey=function(){return fd(this,1)};
Ug.prototype.V=function(){return fd(this,2===id(this,Vg)?2:-1)};
Ug.prototype.setValue=function(a){return hd(this,2,Vg,a)};
var Vg=[2,3,4,5,6];function Wg(a){J.call(this,a)}
u(Wg,J);function Xg(a){J.call(this,a)}
u(Xg,J);function Yg(a){J.call(this,a,-1,Zg)}
u(Yg,J);var Zg=[2];function $g(a){J.call(this,a,-1,ah)}
u($g,J);$g.prototype.getPlayerType=function(){return fd(this,36)};
$g.prototype.setHomeGroupInfo=function(a){return I(this,Yg,81,a)};
var ah=[9,66,24,32,86,100,101];function bh(a){J.call(this,a,-1,ch)}
u(bh,J);var ch=[15,26,28];function dh(a){J.call(this,a)}
u(dh,J);dh.prototype.setToken=function(a){return H(this,2,a)};function eh(a){J.call(this,a,-1,fh)}
u(eh,J);eh.prototype.setSafetyMode=function(a){return H(this,5,a)};
var fh=[12];function gh(a){J.call(this,a,-1,hh)}
u(gh,J);var hh=[12];function ih(a){J.call(this,a,-1,jh)}
u(ih,J);function kh(a){J.call(this,a)}
u(kh,J);kh.prototype.getKey=function(){return od(this,1)};
kh.prototype.V=function(){return od(this,2)};
kh.prototype.setValue=function(a){return H(this,2,a)};
var jh=[4,5];function lh(a){J.call(this,a)}
u(lh,J);function mh(a){J.call(this,a)}
u(mh,J);var nh=[2,3,4];function oh(a){J.call(this,a)}
u(oh,J);function ph(a){J.call(this,a)}
u(ph,J);function qh(a){J.call(this,a)}
u(qh,J);function rh(a){J.call(this,a,-1,sh)}
u(rh,J);var sh=[10,17];function th(a){J.call(this,a)}
u(th,J);function uh(a){J.call(this,a)}
u(uh,J);function vh(a){J.call(this,a)}
u(vh,J);function wh(a){J.call(this,a,442)}
u(wh,J);
var xh=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,352,
353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117,439,441];function yh(a){J.call(this,a)}
u(yh,J);function zh(a){J.call(this,a)}
u(zh,J);zh.prototype.setVideoId=function(a){return hd(this,1,Ah,a)};
zh.prototype.getPlaylistId=function(){return fd(this,2===id(this,Ah)?2:-1)};
var Ah=[1,2];function Bh(a){J.call(this,a,-1,Ch)}
u(Bh,J);var Ch=[3];var Dh=A.window,Eh,Fh,Gh=(null==Dh?void 0:null==(Eh=Dh.yt)?void 0:Eh.config_)||(null==Dh?void 0:null==(Fh=Dh.ytcfg)?void 0:Fh.data_)||{};C("yt.config_",Gh);function Hh(){var a=arguments;1<a.length?Gh[a[0]]=a[1]:1===a.length&&Object.assign(Gh,a[0])}
function N(a,b){return a in Gh?Gh[a]:b}
function Ih(){return N("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS")}
function Jh(){var a=Gh.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;var Kh=[];function Lh(a){Kh.forEach(function(b){return b(a)})}
function Mh(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Nh(b)}}:a}
function Nh(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=N("ERRORS",[]),e.push([a,"ERROR",b,c,d]),Hh("ERRORS",e));Lh(a)}
function Oh(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=N("ERRORS",[]),e.push([a,"WARNING",b,c,d]),Hh("ERRORS",e))}
;var Ph=0;C("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++Ph});var Qh={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Rh(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Qh||(this[b]=a[b]);this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?
d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey}}catch(e){}}
Rh.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Rh.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Rh.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var mb=A.ytEventsEventsListeners||{};C("ytEventsEventsListeners",mb);var Sh=A.ytEventsEventsCounter||{count:0};C("ytEventsEventsCounter",Sh);
function Th(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return kb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Pa(e[4])&&Pa(d)&&nb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function Uh(a){a&&("string"==typeof a&&(a=[a]),D(a,function(b){if(b in mb){var c=mb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Vh()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete mb[b]}}))}
var Vh=bb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Wh(a,b,c){var d=void 0===d?{}:d;if(a&&(a.addEventListener||a.attachEvent)){var e=Th(a,b,c,d);if(!e){e=++Sh.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Rh(h);if(!Ed(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Rh(h);
h.currentTarget=a;return c.call(a,h)};
g=Mh(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Vh()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);mb[e]=[a,b,c,g,d]}}}
;function Xh(a,b){"function"===typeof a&&(a=Mh(a));return window.setTimeout(a,b)}
function Yh(a){"function"===typeof a&&(a=Mh(a));return window.setInterval(a,250)}
;var Zh=/^[\w.]*$/,$h={q:!0,search_query:!0};function ai(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=bi(f[0]||""),h=bi(f[1]||"");g in c?Array.isArray(c[g])?ib(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(q){var k=q,l=f[0],m=String(ai);k.args=[{key:l,value:f[1],query:a,method:ci==m?"unchanged":m}];$h.hasOwnProperty(l)||Oh(k)}}return c}
var ci=String(ai);function di(a){var b=[];jb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];D(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function ei(a){"?"==a.charAt(0)&&(a=a.substr(1));return ai(a,"&")}
function fi(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=ei(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);b=a;a=Ub(e);a?(c=b.indexOf("#"),0>c&&(c=b.length),f=b.indexOf("?"),0>f||f>c?(f=c,e=""):e=b.substring(f+1,c),b=[b.slice(0,f),e,b.slice(c)],c=b[1],b[1]=a?c?c+"&"+a:a:c,a=b[0]+(b[1]?"?"+b[1]:"")+b[2]):a=b;return a+d}
function gi(a){if(!b)var b=window.location.href;var c=a.match(Pb)[1]||null,d=Rb(a);c&&d?(a=a.match(Pb),b=b.match(Pb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?Rb(b)==d&&(Number(b.match(Pb)[4]||null)||null)==(Number(a.match(Pb)[4]||null)||null):!0;return a}
function bi(a){return a&&a.match(Zh)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function P(a){a=hi(a);return"string"===typeof a&&"false"===a?!1:!!a}
function ii(a,b){a=hi(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function hi(a){var b=N("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:N("EXPERIMENT_FLAGS",{})[a]}
function ji(){var a=[],b=N("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=N("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;function ki(a){var b=li;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Qd;e.flash="0";a:{try{var f=b.i.top.location.href}catch(X){f=2;break a}f=f?f===b.j.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?yd:g;try{var h=g.history.length}catch(X){h=0}e.u_his=h;var k;e.u_h=null==(k=yd.screen)?void 0:k.height;var l;e.u_w=null==(l=yd.screen)?void 0:l.width;var m;e.u_ah=null==(m=yd.screen)?void 0:m.availHeight;var q;e.u_aw=null==
(q=yd.screen)?void 0:q.availWidth;var v;e.u_cd=null==(v=yd.screen)?void 0:v.colorDepth}catch(X){}h=b.i;try{var p=h.screenX;var y=h.screenY}catch(X){}try{var z=h.outerWidth;var G=h.outerHeight}catch(X){}try{var K=h.innerWidth;var M=h.innerHeight}catch(X){}try{var O=h.screenLeft;var lb=h.screenTop}catch(X){}try{K=h.innerWidth,M=h.innerHeight}catch(X){}try{var tc=h.screen.availWidth;var wa=h.screen.availTop}catch(X){}p=[O,lb,p,y,tc,wa,z,G,K,M];y=b.i.top;try{var qa=(y||window).document,Y="CSS1Compat"==
qa.compatMode?qa.documentElement:qa.body;var da=(new Cd(Y.clientWidth,Y.clientHeight)).round()}catch(X){da=new Cd(-12245933,-12245933)}qa=da;da={};var ea=void 0===ea?A:ea;Y=new Qe;ea.SVGElement&&ea.document.createElementNS&&Y.set(0);y=Jd();y["allow-top-navigation-by-user-activation"]&&Y.set(1);y["allow-popups-to-escape-sandbox"]&&Y.set(2);ea.crypto&&ea.crypto.subtle&&Y.set(3);ea.TextDecoder&&ea.TextEncoder&&Y.set(4);ea=Re(Y);da.bc=ea;da.bih=qa.height;da.biw=qa.width;da.brdim=p.join();b=b.j;b=(da.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,da.wgl=!!yd.WebGLRenderingContext,da);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var li=new function(){var a=window.document;this.i=window;this.j=a};
C("yt.ads_.signals_.getAdSignalsString",function(a){return di(ki(a))});Date.now();var mi="XMLHttpRequest"in A?function(){return new XMLHttpRequest}:null;
function ni(){if(!mi)return null;var a=mi();return"open"in a?a:null}
;var oi={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},pi="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(Ud)),qi=!1;
function ri(a,b){b=void 0===b?{}:b;var c=gi(a),d=P("web_ajax_ignore_global_headers_if_set"),e;for(e in oi){var f=N(oi[e]);"X-Goog-Visitor-Id"!==e||f||(f=N("VISITOR_DATA"));!f||!c&&Rb(a)||d&&void 0!==b[e]||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!Rb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!Rb(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||
!Rb(a))b["X-YouTube-Ad-Signals"]=di(ki());return b}
function si(a){var b=window.location.search,c=Rb(a);P("debug_handle_relative_url_for_query_forward_killswitch")||c||!gi(a)||(c=document.location.hostname);var d=Qb(a.match(Pb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=ei(b),f={};D(pi,function(g){e[g]&&(f[g]=e[g])});
return fi(a,f||{},!1)}
function ti(a,b){var c=b.format||"JSON";a=ui(a,b);var d=vi(a,b),e=!1,f=wi(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);a:switch(k&&"status"in k?k.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:var l=!0;break a;default:l=!1}var m=null,q=400<=k.status&&500>k.status,v=500<=k.status&&600>k.status;if(l||q||v)m=xi(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=
!!m}m=m||{};q=b.context||A;l?b.onSuccess&&b.onSuccess.call(q,k,m):b.onError&&b.onError.call(q,k,m);b.onFinish&&b.onFinish.call(q,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Xh(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||A,f))},d)}}
function ui(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=N("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=fi(a,b||{},!0);return a}
function vi(a,b){var c=N("XSRF_FIELD_NAME"),d=N("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=N("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||Rb(a)&&!b.withCredentials&&Rb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=ei(e),qb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):Ub(e));if(!(a=e)&&(a=f)){a:{for(var k in f){f=!1;
break a}f=!0}a=!f}!qi&&a&&"POST"!=b.method&&(qi=!0,Nh(Error("AJAX request with postData should use POST")));return e}
function xi(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Oh(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?yi(a):null)e={},D(a.getElementsByTagName("*"),function(g){e[g.tagName]=zi(g)})}d&&Ai(e);
return e}
function Ai(a){if(Pa(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;yb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b];if(void 0===rb){var e=null;var f=A.trustedTypes;if(f&&f.createPolicy){try{e=f.createPolicy("goog#html",{createHTML:Xa,createScript:Xa,createScriptURL:Xa})}catch(g){A.console&&A.console.error(g.message)}rb=e}else rb=e}d=(e=rb)?e.createHTML(d):d;a[c]=new Ob(d)}else Ai(a[b])}}
function yi(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function zi(a){var b="";D(a.childNodes,function(c){b+=c.nodeValue});
return b}
function wi(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Mh(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=ni();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;P("debug_forward_web_query_parameters")&&(a=si(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=ri(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Bi={Nb:"WEB_DISPLAY_MODE_UNKNOWN",Jb:"WEB_DISPLAY_MODE_BROWSER",Lb:"WEB_DISPLAY_MODE_MINIMAL_UI",Mb:"WEB_DISPLAY_MODE_STANDALONE",Kb:"WEB_DISPLAY_MODE_FULLSCREEN"};function Ci(){if(!A.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return A.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":A.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":A.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":A.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;C("ytglobal.prefsUserPrefsPrefs_",B("ytglobal.prefsUserPrefsPrefs_")||{});var Di={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Ei={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Fi={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Gi={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Hi(){var a=A.navigator;return a?a.connection:void 0}
;function Ii(){return"INNERTUBE_API_KEY"in Gh&&"INNERTUBE_API_VERSION"in Gh}
function Ji(){return{innertubeApiKey:N("INNERTUBE_API_KEY"),innertubeApiVersion:N("INNERTUBE_API_VERSION"),Aa:N("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Pa:N("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),ob:N("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:N("INNERTUBE_CONTEXT_CLIENT_VERSION"),Ra:N("INNERTUBE_CONTEXT_HL"),Qa:N("INNERTUBE_CONTEXT_GL"),pb:N("INNERTUBE_HOST_OVERRIDE")||"",rb:!!N("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),qb:!!N("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:N("SERIALIZED_CLIENT_CONFIG_DATA")}}
function Ki(a){var b={client:{hl:a.Ra,gl:a.Qa,clientName:a.Pa,clientVersion:a.innertubeContextClientVersion,configInfo:a.Aa}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=A.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=N("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=ji();0<c.length&&(b.request={internalExperimentFlags:c});Li(a,void 0,b);Mi(void 0,b);Ni(a,void 0,b);Oi(void 0,b);N("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&
(b.user={onBehalfOfUser:N("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=t(Object.entries(ei(N("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=t(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Pi(a){var b=new gh,c=new $g;H(c,1,a.Ra);H(c,2,a.Qa);H(c,16,a.ob);H(c,17,a.innertubeContextClientVersion);if(a.Aa){var d=a.Aa,e=new Wg;d.coldConfigData&&H(e,1,d.coldConfigData);d.appInstallData&&H(e,6,d.appInstallData);d.coldHashData&&H(e,3,d.coldHashData);d.hotHashData&&H(e,5,d.hotHashData);I(c,Wg,62,e)}(d=A.devicePixelRatio)&&1!=d&&H(c,65,d);d=N("EXPERIMENTS_TOKEN","");""!==d&&H(c,54,d);d=ji();if(0<d.length){e=new bh;for(var f=0;f<d.length;f++){var g=new Ug;H(g,1,d[f].key);g.setValue(d[f].value);
nd(e,15,Ug,g)}I(b,bh,5,e)}Li(a,c);Mi(c);Ni(a,c);Oi(c);N("DELEGATED_SESSION_ID")&&!P("pageid_as_header_web")&&(a=new eh,H(a,3,N("DELEGATED_SESSION_ID")));a=t(Object.entries(ei(N("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=t(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?H(c,12,e):"cmodel"===d?H(c,13,e):"cbr"===d?H(c,87,e):"cbrver"===d?H(c,88,e):"cos"===d?H(c,18,e):"cosver"===d?H(c,19,e):"cplatform"===d&&H(c,42,e);I(b,$g,1,c);return b}
function Li(a,b,c){a=a.Pa;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=jd(b,Xg,96)||new Xg;var d=Ci();d=Object.keys(Bi).indexOf(d);d=-1===d?null:d;null!==d&&H(c,3,d);I(b,Xg,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=Ci())}
function Mi(a,b){var c;if(P("web_log_memory_total_kbytes")&&(null==(c=A.navigator)?0:c.deviceMemory)){var d;c=null==(d=A.navigator)?void 0:d.deviceMemory;a?H(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Ni(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=jd(b,Wg,62))?d:new Wg;H(c,6,a.appInstallData);I(b,Wg,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Oi(a,b){a:{var c=Hi();if(c){var d=Di[c.type||"unknown"]||"CONN_UNKNOWN";c=Di[c.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===d&&"CONN_UNKNOWN"!==c&&(d=c);if("CONN_UNKNOWN"!==d)break a;if("CONN_UNKNOWN"!==c){d=c;break a}}d=void 0}d&&(a?H(a,61,Ei[d]):b&&(b.client.connectionType=d));P("web_log_effective_connection_type")&&(d=Hi(),d=null!=d&&d.effectiveType?Gi.hasOwnProperty(d.effectiveType)?Gi[d.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,d&&(a?H(a,94,Fi[d]):
b&&(b.client.effectiveConnectionType=d)))}
function Qi(a,b,c){c=void 0===c?{}:c;var d={};N("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":N("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||N("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Pb||N("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().Ob:b=de([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=N("SESSION_INDEX",0),P("pageid_as_header_web")&&(d["X-Goog-PageId"]=N("DELEGATED_SESSION_ID")));return d}
;function Ri(a){a=Object.assign({},a);delete a.Authorization;var b=de();if(b){var c=new Af;c.update(N("INNERTUBE_API_KEY"));c.update(b);a.hash=yc(c.digest(),3)}return a}
;function Si(a){var b=new Ng;(b=b.isAvailable()?a?new Tg(b,a):b:null)||(a=new Og(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.i=(a=b)?new Jg(a):null;this.j=document.domain||window.location.hostname}
Si.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.i)try{this.i.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(kg(b))}catch(f){return}else e=escape(b);b=this.j;ae.set(""+a,e,{Ba:c,path:"/",domain:void 0===b?"youtube.com":b,secure:!1})};
Si.prototype.get=function(a,b){var c=void 0,d=!this.i;if(!d)try{c=this.i.get(a)}catch(e){d=!0}if(d&&(c=ae.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Si.prototype.remove=function(a){this.i&&this.i.remove(a);var b=this.j;ae.remove(""+a,"/",void 0===b?"youtube.com":b)};var Ti=window,R=Ti.ytcsi&&Ti.ytcsi.now?Ti.ytcsi.now:Ti.performance&&Ti.performance.timing&&Ti.performance.now&&Ti.performance.timing.navigationStart?function(){return Ti.performance.timing.navigationStart+Ti.performance.now()}:function(){return(new Date).getTime()};var Ui;function Vi(){Ui||(Ui=new Si("yt.innertube"));return Ui}
function Wi(a,b,c,d){if(d)return null;d=Vi().get("nextId",!0)||1;var e=Vi().get("requests",!0)||{};e[d]={method:a,request:b,authState:Ri(c),requestTime:Math.round(R())};Vi().set("nextId",d+1,86400,!0);Vi().set("requests",e,86400,!0);return d}
function Xi(a){var b=Vi().get("requests",!0)||{};delete b[a];Vi().set("requests",b,86400,!0)}
function Yi(a){var b=Vi().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=Ri(Qi(!1));nb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),Zi(a,d.method,e,{}));delete b[c]}}Vi().set("requests",b,86400,!0)}}
;function $i(){}
$i.prototype.P=function(a,b){return aj(a,1,b)};
function bj(a,b){aj(a,2,b)}
;function cj(){$i.apply(this,arguments)}
u(cj,$i);function dj(){cj.i||(cj.i=new cj);return cj.i}
function aj(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Xh(a,c||0)}
cj.prototype.Z=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
cj.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};var Pe=dj();var ej=sc||uc;var fj=function(){var a;return function(){a||(a=new Si("ytidb"));return a}}();
function gj(){var a;return null==(a=fj())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var hj=[],ij=!1;function jj(a){ij||(hj.push({type:"ERROR",payload:a}),10<hj.length&&hj.shift())}
function kj(a,b){ij||(hj.push({type:"EVENT",eventType:a,payload:b}),10<hj.length&&hj.shift())}
;function lj(a){var b=Ia.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
u(lj,Error);function mj(){try{return nj(),!0}catch(a){return!1}}
function nj(){if(void 0!==N("DATASYNC_ID"))return N("DATASYNC_ID");throw new lj("Datasync ID not set","unknown");}
;function oj(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function pj(a){return a.substr(0,a.indexOf(":"))||a}
;var qj={},rj=(qj.AUTH_INVALID="No user identifier specified.",qj.EXPLICIT_ABORT="Transaction was explicitly aborted.",qj.IDB_NOT_SUPPORTED="IndexedDB is not supported.",qj.MISSING_INDEX="Index not created.",qj.MISSING_OBJECT_STORES="Object stores not created.",qj.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",qj.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",qj.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
qj.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",qj.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",qj.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",qj.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",qj),sj={},tj=(sj.AUTH_INVALID="ERROR",sj.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",sj.EXPLICIT_ABORT="IGNORED",sj.IDB_NOT_SUPPORTED="ERROR",sj.MISSING_INDEX=
"WARNING",sj.MISSING_OBJECT_STORES="ERROR",sj.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",sj.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",sj.QUOTA_EXCEEDED="WARNING",sj.QUOTA_MAYBE_EXCEEDED="WARNING",sj.UNKNOWN_ABORT="WARNING",sj.INCOMPATIBLE_DB_VERSION="WARNING",sj),uj={},vj=(uj.AUTH_INVALID=!1,uj.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,uj.EXPLICIT_ABORT=!1,uj.IDB_NOT_SUPPORTED=!1,uj.MISSING_INDEX=!1,uj.MISSING_OBJECT_STORES=!1,uj.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,uj.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,uj.QUOTA_EXCEEDED=!1,uj.QUOTA_MAYBE_EXCEEDED=!0,uj.UNKNOWN_ABORT=!0,uj.INCOMPATIBLE_DB_VERSION=!1,uj);function T(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?rj[a]:c;d=void 0===d?tj[a]:d;e=void 0===e?vj[a]:e;lj.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.i=e;Object.setPrototypeOf(this,T.prototype)}
u(T,lj);function wj(a,b){T.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},rj.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,wj.prototype)}
u(wj,T);function xj(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,xj.prototype)}
u(xj,Error);var yj=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function zj(a,b,c,d){b=pj(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof T)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new T("QUOTA_EXCEEDED",a);if(vc&&"UnknownError"===e.name)return new T("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof xj)return new T("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&yj.some(function(f){return e.message.includes(f)}))return new T("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new T("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Tb:e.name})];e.level="WARNING";return e}
function Aj(a,b,c){var d=gj();return new T("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Bj(a){if(!a)throw Error();throw a;}
function Cj(a){return a}
function Dj(a){this.i=a}
function U(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=t(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=t(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.i=[];this.onRejected=[];a=a.i;try{a(c,b)}catch(e){b(e)}}
U.all=function(a){return new U(new Dj(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={Y:0};f.Y<a.length;f={Y:f.Y},++f.Y)Ej(U.resolve(a[f.Y]).then(function(g){return function(h){d[g.Y]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
U.resolve=function(a){return new U(new Dj(function(b,c){a instanceof U?a.then(b,c):b(a)}))};
U.reject=function(a){return new U(new Dj(function(b,c){c(a)}))};
U.prototype.then=function(a,b){var c=this,d=null!=a?a:Cj,e=null!=b?b:Bj;return new U(new Dj(function(f,g){"PENDING"===c.state.status?(c.i.push(function(){Fj(c,c,d,f,g)}),c.onRejected.push(function(){Gj(c,c,e,f,g)})):"FULFILLED"===c.state.status?Fj(c,c,d,f,g):"REJECTED"===c.state.status&&Gj(c,c,e,f,g)}))};
function Ej(a,b){a.then(void 0,b)}
function Fj(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof U?Hj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Gj(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof U?Hj(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Hj(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof U?Hj(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Ij(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Jj(a){return new Promise(function(b,c){Ij(a,b,c)})}
function V(a){return new U(new Dj(function(b,c){Ij(a,b,c)}))}
;function Kj(a,b){return new U(new Dj(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Lj(a,b){this.i=a;this.options=b;this.transactionCount=0;this.l=Math.round(R());this.j=!1}
n=Lj.prototype;n.add=function(a,b,c){return Ak(this,[a],{mode:"readwrite",I:!0},function(d){return d.objectStore(a).add(b,c)})};
n.clear=function(a){return Ak(this,[a],{mode:"readwrite",I:!0},function(b){return b.objectStore(a).clear()})};
n.close=function(){this.i.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
n.count=function(a,b){return Ak(this,[a],{mode:"readonly",I:!0},function(c){return c.objectStore(a).count(b)})};
function Bk(a,b,c){a=a.i.createObjectStore(b,c);return new Ck(a)}
n.delete=function(a,b){return Ak(this,[a],{mode:"readwrite",I:!0},function(c){return c.objectStore(a).delete(b)})};
n.get=function(a,b){return Ak(this,[a],{mode:"readonly",I:!0},function(c){return c.objectStore(a).get(b)})};
function Dk(a,b){return Ak(a,["LogsRequestsStore"],{mode:"readwrite",I:!0},function(c){c=c.objectStore("LogsRequestsStore");return V(c.i.put(b,void 0))})}
n.objectStoreNames=function(){return Array.from(this.i.objectStoreNames)};
function Ak(a,b,c,d){var e,f,g,h,k,l,m,q,v,p,y,z;return x(function(G){switch(G.i){case 1:var K={mode:"readonly",I:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?K.mode=c:Object.assign(K,c);e=K;a.transactionCount++;f=e.I?3:1;g=0;case 2:if(h){G.v(3);break}g++;k=Math.round(R());xa(G,4);l=a.i.transaction(b,e.mode);K=new Ek(l);K=Fk(K,d);return w(G,K,6);case 6:return m=G.j,q=Math.round(R()),Gk(a,k,q,g,void 0,b.join(),e),G.return(m);case 4:v=za(G);p=Math.round(R());y=zj(v,a.i.name,b.join(),a.i.version);
if((z=y instanceof T&&!y.i)||g>=f)Gk(a,k,p,g,y,b.join(),e),h=y;G.v(2);break;case 3:return G.return(Promise.reject(h))}})}
function Gk(a,b,c,d,e,f,g){b=c-b;e?(e instanceof T&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&kj("QUOTA_EXCEEDED",{dbName:pj(a.i.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof T&&"UNKNOWN_ABORT"===e.type&&(c-=a.l,0>c&&c>=Math.pow(2,31)&&(c=0),kj("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.j=!0),Hk(a,!1,d,f,b,g.tag),jj(e)):Hk(a,!0,d,f,b,g.tag)}
function Hk(a,b,c,d,e,f){kj("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.j,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
n.getName=function(){return this.i.name};
function Ck(a){this.i=a}
n=Ck.prototype;n.add=function(a,b){return V(this.i.add(a,b))};
n.autoIncrement=function(){return this.i.autoIncrement};
n.clear=function(){return V(this.i.clear()).then(function(){})};
n.count=function(a){return V(this.i.count(a))};
function Ik(a,b){return Jk(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
n.delete=function(a){return a instanceof IDBKeyRange?Ik(this,a):V(this.i.delete(a))};
n.get=function(a){return V(this.i.get(a))};
n.index=function(a){try{return new Kk(this.i.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new xj(a,this.i.name);throw b;}};
n.getName=function(){return this.i.name};
n.keyPath=function(){return this.i.keyPath};
function Jk(a,b,c){a=a.i.openCursor(b.query,b.direction);return Lk(a).then(function(d){return Kj(d,c)})}
function Ek(a){var b=this;this.i=a;this.l=new Map;this.j=!1;this.done=new Promise(function(c,d){b.i.addEventListener("complete",function(){c()});
b.i.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.i.error)});
b.i.addEventListener("abort",function(){var e=b.i.error;if(e)d(e);else if(!b.j){e=T;for(var f=b.i.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.i.db.name,mode:b.i.mode});d(e)}})})}
function Fk(a,b){var c=new Promise(function(d,e){try{Ej(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return t(d).next().value})}
Ek.prototype.abort=function(){this.i.abort();this.j=!0;throw new T("EXPLICIT_ABORT");};
Ek.prototype.objectStore=function(a){a=this.i.objectStore(a);var b=this.l.get(a);b||(b=new Ck(a),this.l.set(a,b));return b};
function Kk(a){this.i=a}
n=Kk.prototype;n.count=function(a){return V(this.i.count(a))};
n.delete=function(a){return Mk(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
n.get=function(a){return V(this.i.get(a))};
n.getKey=function(a){return V(this.i.getKey(a))};
n.keyPath=function(){return this.i.keyPath};
n.unique=function(){return this.i.unique};
function Mk(a,b,c){a=a.i.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Lk(a).then(function(d){return Kj(d,c)})}
function Nk(a,b){this.request=a;this.cursor=b}
function Lk(a){return V(a).then(function(b){return b?new Nk(a,b):null})}
n=Nk.prototype;n.advance=function(a){this.cursor.advance(a);return Lk(this.request)};
n.continue=function(a){this.cursor.continue(a);return Lk(this.request)};
n.delete=function(){return V(this.cursor.delete()).then(function(){})};
n.getKey=function(){return this.cursor.key};
n.V=function(){return this.cursor.value};
n.update=function(a){return V(this.cursor.update(a))};function Ok(a,b,c){return new Promise(function(d,e){function f(){v||(v=new Lj(g.result,{closed:q}));return v}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.wb,m=c.upgrade,q=c.closed,v;g.addEventListener("upgradeneeded",function(p){try{if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");p.dataLoss&&"none"!==p.dataLoss&&kj("IDB_DATA_CORRUPTED",{reason:p.dataLossMessage||"unknown reason",dbName:pj(a)});var y=f(),z=new Ek(g.transaction);
m&&m(y,function(G){return p.oldVersion<G&&p.newVersion>=G},z);
z.done.catch(function(G){e(G)})}catch(G){e(G)}});
g.addEventListener("success",function(){var p=g.result;k&&p.addEventListener("versionchange",function(){k(f())});
p.addEventListener("close",function(){kj("IDB_UNEXPECTEDLY_CLOSED",{dbName:pj(a),dbVersion:p.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Pk(a,b,c){c=void 0===c?{}:c;return Ok(a,b,c)}
function Qk(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.i)return xa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),w(g,Jj(c),4);
if(2!=g.i)return ya(g,0);f=za(g);throw zj(f,a,"",-1);})}
;function Rk(a){return new Promise(function(b){bj(function(){b()},a)})}
function Sk(a,b){this.name=a;this.options=b;this.m=!0;this.u=this.s=0;this.j=500}
Sk.prototype.l=function(a,b,c){c=void 0===c?{}:c;return Pk(a,b,c)};
Sk.prototype.delete=function(a){a=void 0===a?{}:a;return Qk(this.name,a)};
function Tk(a,b){return new T("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Uk(a,b){if(!b)throw Aj("openWithToken",pj(a.name));return Vk(a)}
function Vk(a){function b(){var f,g,h,k,l,m,q,v,p,y;return x(function(z){switch(z.i){case 1:return g=null!=(f=Error().stack)?f:"",xa(z,2),w(z,a.l(a.name,a.options.version,d),4);case 4:h=z.j;for(var G=a.options,K=[],M=t(Object.keys(G.ia)),O=M.next();!O.done;O=M.next()){O=O.value;var lb=G.ia[O],tc=void 0===lb.ub?Number.MAX_VALUE:lb.ub;!(h.i.version>=lb.ya)||h.i.version>=tc||h.i.objectStoreNames.contains(O)||K.push(O)}k=K;if(0===k.length){z.v(5);break}l=Object.keys(a.options.ia);m=h.objectStoreNames();
if(a.u<ii("ytidb_reopen_db_retries",0))return a.u++,h.close(),jj(new T("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:l,foundObjectStores:m})),z.return(b());if(!(a.s<ii("ytidb_remake_db_retries",1))){z.v(6);break}a.s++;if(!P("ytidb_remake_db_enable_backoff_delay")){z.v(7);break}return w(z,Rk(a.j),8);case 8:a.j*=2;case 7:return w(z,a.delete(),9);case 9:return jj(new T("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:l,foundObjectStores:m})),z.return(b());
case 6:throw new wj(m,l);case 5:return z.return(h);case 2:q=za(z);if(q instanceof DOMException?"VersionError"!==q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){z.v(10);break}return w(z,a.l(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:v=z.j;p=v.i.version;if(void 0!==a.options.version&&p>a.options.version+1)throw v.close(),
a.m=!1,Tk(a,p);return z.return(v);case 10:throw c(),q instanceof Error&&!P("ytidb_async_stack_killswitch")&&(q.stack=q.stack+"\n"+g.substring(g.indexOf("\n")+1)),zj(q,a.name,"",null!=(y=a.options.version)?y:-1);}})}
function c(){a.i===e&&(a.i=void 0)}
if(!a.m)throw Tk(a);if(a.i)return a.i;var d={blocking:function(f){f.close()},
closed:c,wb:c,upgrade:a.options.upgrade};var e=b();a.i=e;return a.i}
;var Wk=new Sk("YtIdbMeta",{ia:{databases:{ya:1}},upgrade:function(a,b){b(1)&&Bk(a,"databases",{keyPath:"actualName"})}});
function Xk(a,b){var c;return x(function(d){if(1==d.i)return w(d,Uk(Wk,b),2);c=d.j;return d.return(Ak(c,["databases"],{I:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return V(f.i.put(a,void 0)).then(function(){})})}))})}
function Yk(a,b){var c;return x(function(d){if(1==d.i)return a?w(d,Uk(Wk,b),2):d.return();c=d.j;return d.return(c.delete("databases",a))})}
function Zk(a,b){var c,d;return x(function(e){return 1==e.i?(c=[],w(e,Uk(Wk,b),2)):3!=e.i?(d=e.j,w(e,Ak(d,["databases"],{I:!0,mode:"readonly"},function(f){c.length=0;return Jk(f.objectStore("databases"),{},function(g){a(g.V())&&c.push(g.V());return g.continue()})}),3)):e.return(c)})}
function $k(a){return Zk(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var al,bl=new function(){}(new function(){});
function cl(){var a,b,c,d;return x(function(e){switch(e.i){case 1:a=gj();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=ej)f=/WebKit\/([0-9]+)/.exec(Lb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Lb()),f=!(f&&602<=parseInt(f[1],10)));if(f||gc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
xa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(e,Xk(d,bl),4);case 4:return w(e,Yk("yt-idb-test-do-not-use",bl),5);case 5:return e.return(!0);case 2:return za(e),e.return(!1)}})}
function dl(){if(void 0!==al)return al;ij=!0;return al=cl().then(function(a){ij=!1;var b;if(null!=(b=fj())&&b.i){var c;b={hasSucceededOnce:(null==(c=gj())?void 0:c.hasSucceededOnce)||a};var d;null==(d=fj())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function el(){return B("ytglobal.idbToken_")||void 0}
function fl(){var a=el();return a?Promise.resolve(a):dl().then(function(b){(b=b?bl:void 0)&&C("ytglobal.idbToken_",b);return b})}
;new lg;function gl(a){if(!mj())throw a=new T("AUTH_INVALID",{dbName:a}),jj(a),a;var b=nj();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function hl(a,b,c,d){var e,f,g,h,k,l;return x(function(m){switch(m.i){case 1:return f=null!=(e=Error().stack)?e:"",w(m,fl(),2);case 2:g=m.j;if(!g)throw h=Aj("openDbImpl",a,b),P("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),jj(h),h;oj(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:gl(a);xa(m,3);return w(m,Xk(k,g),5);case 5:return w(m,Pk(k.actualName,b,d),6);case 6:return m.return(m.j);case 3:return l=za(m),xa(m,7),w(m,Yk(k.actualName,g),9);case 9:ya(m,
8);break;case 7:za(m);case 8:throw l;}})}
function il(a,b,c){c=void 0===c?{}:c;return hl(a,b,!1,c)}
function jl(a,b,c){c=void 0===c?{}:c;return hl(a,b,!0,c)}
function kl(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.i)return w(e,fl(),2);if(3!=e.i){c=e.j;if(!c)return e.return();oj(a);d=gl(a);return w(e,Qk(d.actualName,b),3)}return w(e,Yk(d.actualName,c),0)})}
function ll(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.i?w(e,Qk(d.actualName,b),2):w(e,Yk(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function ml(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.i)return w(d,fl(),2);if(3!=d.i){b=d.j;if(!b)return d.return();oj("LogsDatabaseV2");return w(d,$k(b),3)}c=d.j;return w(d,ll(c,a,b),0)})}
function nl(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.i)return w(d,fl(),2);if(3!=d.i){c=d.j;if(!c)return d.return();oj(a);return w(d,Qk(a,b),3)}return w(d,Yk(a,c),0)})}
;function ol(a){this.oa=this.i=!1;this.potentialEsfErrorCounter=this.j=0;this.handleError=function(){};
this.ba=function(){};
this.now=Date.now;this.fa=!1;var b;this.Za=null!=(b=a.Za)?b:100;var c;this.Ya=null!=(c=a.Ya)?c:1;var d;this.Wa=null!=(d=a.Wa)?d:2592E6;var e;this.Va=null!=(e=a.Va)?e:12E4;var f;this.Xa=null!=(f=a.Xa)?f:5E3;var g;this.B=null!=(g=a.B)?g:void 0;this.sa=!!a.sa;var h;this.ra=null!=(h=a.ra)?h:.1;var k;this.wa=null!=(k=a.wa)?k:10;a.handleError&&(this.handleError=a.handleError);a.ba&&(this.ba=a.ba);a.fa&&(this.fa=a.fa);a.oa&&(this.oa=a.oa);this.C=a.C;this.K=a.K;this.D=a.D;this.G=a.G;this.S=a.S;this.Ea=a.Ea;
this.Da=a.Da;pl(this)&&(!this.C||this.C("networkless_logging"))&&ql(this)}
function ql(a){pl(a)&&!a.fa&&(a.i=!0,a.sa&&Math.random()<=a.ra&&a.D.ib(a.B),rl(a),a.G.F()&&a.ma(),a.G.X(a.Ea,a.ma.bind(a)),a.G.X(a.Da,a.Ka.bind(a)))}
n=ol.prototype;n.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(pl(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.D.set(d,this.B).then(function(e){d.id=e;c.G.F()&&sl(c,d)}).catch(function(e){sl(c,d);
tl(c,e)})}else this.S(a,b)};
n.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(pl(this)&&this.i){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.C&&this.C("nwl_skip_retry")&&(e.skipRetry=c);if(this.G.F()||this.C&&this.C("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.i)return w(k,d.D.set(e,d.B).catch(function(l){tl(d,l)}),2);
f(g,h);k.i=0})}}this.S(a,b,e.skipRetry)}else this.D.set(e,this.B).catch(function(g){d.S(a,b,e.skipRetry);
tl(d,g)})}else this.S(a,b,this.C&&this.C("nwl_skip_retry")&&c)};
n.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(pl(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.D.aa(d.id,c.B):e=!0;c.G.R&&c.C&&c.C("vss_network_hint")&&c.G.R(!0);f(g,h)};
this.S(d.url,d.options);this.D.set(d,this.B).then(function(g){d.id=g;e&&c.D.aa(d.id,c.B)}).catch(function(g){tl(c,g)})}else this.S(a,b)};
n.ma=function(){var a=this;if(!pl(this))throw Aj("throttleSend");this.j||(this.j=this.K.P(function(){var b;return x(function(c){if(1==c.i)return w(c,a.D.Oa("NEW",a.B),2);if(3!=c.i)return b=c.j,b?w(c,sl(a,b),3):(a.Ka(),c.return());a.j&&(a.j=0,a.ma());c.i=0})},this.Za))};
n.Ka=function(){this.K.Z(this.j);this.j=0};
function sl(a,b){var c,d;return x(function(e){switch(e.i){case 1:if(!pl(a))throw c=Aj("immediateSend"),c;if(void 0===b.id){e.v(2);break}return w(e,a.D.tb(b.id,a.B),3);case 3:(d=e.j)?b=d:a.ba(Error("The request cannot be found in the database."));case 2:if(ul(a,b,a.Wa)){e.v(4);break}a.ba(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.v(5);break}return w(e,a.D.aa(b.id,a.B),5);case 5:return e.return();case 4:b.skipRetry||(b=vl(a,b));if(!b){e.v(0);break}if(!b.skipRetry||
void 0===b.id){e.v(8);break}return w(e,a.D.aa(b.id,a.B),8);case 8:a.S(b.url,b.options,!!b.skipRetry),e.i=0}})}
function vl(a,b){if(!pl(a))throw Aj("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return x(function(l){switch(l.i){case 1:g=wl(f);if(!(a.C&&a.C("nwl_consider_error_code")&&g||a.C&&!a.C("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.wa)){l.v(2);break}if(!a.G.ka){l.v(3);break}return w(l,a.G.ka(),3);case 3:if(a.G.F()){l.v(2);break}c(e,f);if(!a.C||!a.C("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){l.v(6);break}return w(l,a.D.Fa(b.id,a.B,!1),6);case 6:return l.return();case 2:if(a.C&&a.C("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.wa)return l.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){l.v(8);break}return b.sendCount<a.Ya?w(l,a.D.Fa(b.id,a.B),12):w(l,a.D.aa(b.id,a.B),8);case 12:a.K.P(function(){a.G.F()&&a.ma()},a.Xa);
case 8:c(e,f),l.i=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.i)return void 0===(null==(g=b)?void 0:g.id)?h.v(2):w(h,a.D.aa(b.id,a.B),2);a.G.R&&a.C&&a.C("vss_network_hint")&&a.G.R(!0);d(e,f);h.i=0})};
return b}
function ul(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function rl(a){if(!pl(a))throw Aj("retryQueuedRequests");a.D.Oa("QUEUED",a.B).then(function(b){b&&!ul(a,b,a.Va)?a.K.P(function(){return x(function(c){if(1==c.i)return void 0===b.id?c.v(2):w(c,a.D.Fa(b.id,a.B),2);rl(a);c.i=0})}):a.G.F()&&a.ma()})}
function tl(a,b){a.ab&&!a.G.F()?a.ab(b):a.handleError(b)}
function pl(a){return!!a.B||a.oa}
function wl(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;var xl=B("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.na;L.prototype.publish=L.prototype.ca;L.prototype.clear=L.prototype.clear;C("ytPubsub2Pubsub2Instance",xl);C("ytPubsub2Pubsub2SubscribedKeys",B("ytPubsub2Pubsub2SubscribedKeys")||{});C("ytPubsub2Pubsub2TopicToKeys",B("ytPubsub2Pubsub2TopicToKeys")||{});C("ytPubsub2Pubsub2IsAsync",B("ytPubsub2Pubsub2IsAsync")||{});C("ytPubsub2Pubsub2SkipSubKey",null);function yl(a,b){Sk.call(this,a,b);this.options=b;oj(a)}
u(yl,Sk);function zl(a,b){var c;return function(){c||(c=new yl(a,b));return c}}
yl.prototype.l=function(a,b,c){c=void 0===c?{}:c;return(this.options.Ga?jl:il)(a,b,Object.assign({},c))};
yl.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Ga?nl:kl)(this.name,a)};
function Al(a,b){return zl(a,b)}
;var Bl;
function Cl(){if(Bl)return Bl();var a={};Bl=Al("LogsDatabaseV2",{ia:(a.LogsRequestsStore={ya:2},a),Ga:!1,upgrade:function(b,c,d){c(2)&&Bk(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.i.indexNames.contains("newRequest")&&d.i.deleteIndex("newRequest"),d.i.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.i.objectStoreNames.contains("sapisid")&&b.i.deleteObjectStore("sapisid");c(9)&&b.i.objectStoreNames.contains("SWHealthLog")&&b.i.deleteObjectStore("SWHealthLog")},
version:9});return Bl()}
;function Dl(a){return Uk(Cl(),a)}
function El(a,b){var c,d,e,f;return x(function(g){if(1==g.i)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,Dl(b),2);if(3!=g.i)return d=g.j,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:N("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,Dk(d,e),3);f=g.j;c.xb=R();Fl(c);return g.return(f)})}
function Gl(a,b){var c,d,e,f,g,h,k;return x(function(l){if(1==l.i)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(l,Dl(b),2);if(3!=l.i)return d=l.j,e=N("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,R()],h=IDBKeyRange.bound(f,g),k=void 0,w(l,Ak(d,["LogsRequestsStore"],{mode:"readwrite",I:!0},function(m){return Mk(m.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(q){q.V()&&(k=q.V(),"NEW"===a&&(k.status="QUEUED",q.update(k)))})}),
3);
c.xb=R();Fl(c);return l.return(k)})}
function Hl(a,b){var c;return x(function(d){if(1==d.i)return w(d,Dl(b),2);c=d.j;return d.return(Ak(c,["LogsRequestsStore"],{mode:"readwrite",I:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",V(f.i.put(g,void 0)).then(function(){return g})})}))})}
function Il(a,b,c){c=void 0===c?!0:c;var d;return x(function(e){if(1==e.i)return w(e,Dl(b),2);d=e.j;return e.return(Ak(d,["LogsRequestsStore"],{mode:"readwrite",I:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),V(g.i.put(h,void 0)).then(function(){return h})):U.resolve(void 0)})}))})}
function Jl(a,b){var c;return x(function(d){if(1==d.i)return w(d,Dl(b),2);c=d.j;return d.return(c.delete("LogsRequestsStore",a))})}
function Kl(a){var b,c;return x(function(d){if(1==d.i)return w(d,Dl(a),2);b=d.j;c=R()-2592E6;return w(d,Ak(b,["LogsRequestsStore"],{mode:"readwrite",I:!0},function(e){return Jk(e.objectStore("LogsRequestsStore"),{},function(f){if(f.V().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Ll(){x(function(a){return w(a,ml(),0)})}
function Fl(a){if(!P("nwl_csi_killswitch")&&.01>=Math.random()){var b=B("ytPubsub2Pubsub2Instance");b&&b.publish.call(b,"nwl_transaction_latency_payload".toString(),"nwl_transaction_latency_payload",a)}}
;var Ml={},Nl=Al("ServiceWorkerLogsDatabase",{ia:(Ml.SWHealthLog={ya:1},Ml),Ga:!0,upgrade:function(a,b){b(1)&&Bk(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).i.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Ol(a){return Uk(Nl(),a)}
function Pl(a){var b,c;x(function(d){if(1==d.i)return w(d,Ol(a),2);b=d.j;c=R()-2592E6;return w(d,Ak(b,["SWHealthLog"],{mode:"readwrite",I:!0},function(e){return Jk(e.objectStore("SWHealthLog"),{},function(f){if(f.V().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Ql(a){var b;return x(function(c){if(1==c.i)return w(c,Ol(a),2);b=c.j;return w(c,b.clear("SWHealthLog"),0)})}
;var Rl={},Sl=0;
function Tl(a){var b=void 0===b?"":b;var c=void 0===c?!1:c;if(a)if(b)wi(a,void 0,"POST",b);else if(N("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))wi(a,void 0,"GET","",void 0,void 0,c);else{b:{try{var d=new $a({url:a});if(d.l&&d.j||d.m){var e=Qb(a.match(Pb)[5]||null);var f=!(!e||!e.endsWith("/aclk")||"1"!==$b(a,"ri"));break b}}catch(h){}f=!1}if(f){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var g=!0;break b}}catch(h){}g=!1}b=g?!0:!1}else b=!1;b||Ul(a)}}
function Ul(a){var b=new Image,c=""+Sl++;Rl[c]=b;b.onload=b.onerror=function(){delete Rl[c]};
b.src=a}
;function W(){this.i=new Map;this.j=!1}
function Vl(){if(!W.i){var a=B("yt.networkRequestMonitor.instance")||new W;C("yt.networkRequestMonitor.instance",a);W.i=a}return W.i}
W.prototype.requestComplete=function(a,b){b&&(this.j=!0);a=this.removeParams(a);this.i.get(a)||this.i.set(a,b)};
W.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.i.get(a))?!1:!1===a&&this.j?!0:null};
W.prototype.removeParams=function(a){return a.split("?")[0]};
W.prototype.removeParams=W.prototype.removeParams;W.prototype.isEndpointCFR=W.prototype.isEndpointCFR;W.prototype.requestComplete=W.prototype.requestComplete;W.getInstance=Vl;var Wl;function Xl(){Wl||(Wl=new Si("yt.offline"));return Wl}
function Yl(a){if(P("offline_error_handling")){var b=Xl().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Xl().set("errors",b,2592E3,!0)}}
;function Z(){Ie.call(this);var a=this;this.m=!1;this.j=Oe();this.j.X("networkstatus-online",function(){if(a.m&&P("offline_error_handling")){var b=Xl().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new lj(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Nh(d)}Xl().set("errors",{},2592E3,!0)}}})}
u(Z,Ie);function Zl(){if(!Z.i){var a=B("yt.networkStatusManager.instance")||new Z;C("yt.networkStatusManager.instance",a);Z.i=a}return Z.i}
n=Z.prototype;n.F=function(){return this.j.F()};
n.R=function(a){this.j.j=a};
n.nb=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
n.kb=function(){this.m=!0};
n.X=function(a,b){return this.j.X(a,b)};
n.ka=function(a){a=Me(this.j,a);a.then(function(b){P("use_cfr_monitor")&&Vl().requestComplete("generate_204",b)});
return a};
Z.prototype.sendNetworkCheckRequest=Z.prototype.ka;Z.prototype.listen=Z.prototype.X;Z.prototype.enableErrorFlushing=Z.prototype.kb;Z.prototype.getWindowStatus=Z.prototype.nb;Z.prototype.networkStatusHint=Z.prototype.R;Z.prototype.isNetworkAvailable=Z.prototype.F;Z.getInstance=Zl;function $l(a){a=void 0===a?{}:a;Ie.call(this);var b=this;this.j=this.A=0;this.m=Zl();var c=B("yt.networkStatusManager.instance.listen").bind(this.m);c&&(a.xa?(this.xa=a.xa,c("networkstatus-online",function(){am(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){am(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Je(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Je(b,"publicytnetworkstatus-offline")})))}
u($l,Ie);$l.prototype.F=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.m)():!0};
$l.prototype.R=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.m);b&&b(a)};
$l.prototype.ka=function(a){var b=this,c;return x(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.m);return P("skip_network_check_if_cfr")&&Vl().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.R((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.F())})):c?d.return(c(a)):d.return(!0)})};
function am(a,b){a.xa?a.j?(Pe.Z(a.A),a.A=Pe.P(function(){a.u!==b&&(Je(a,b),a.u=b,a.j=R())},a.xa-(R()-a.j))):(Je(a,b),a.u=b,a.j=R()):Je(a,b)}
;var bm;function cm(){ol.call(this,{D:{ib:Kl,aa:Jl,Oa:Gl,tb:Hl,Fa:Il,set:El},G:dm(),handleError:Nh,ba:Oh,S:em,now:R,ab:Yl,K:dj(),Ea:"publicytnetworkstatus-online",Da:"publicytnetworkstatus-offline",sa:!0,ra:.1,wa:ii("potential_esf_error_limit",10),C:P,fa:!(mj()&&"www.youtube-nocookie.com"!==Rb(document.location.toString()))});this.l=new lg;P("networkless_immediately_drop_all_requests")&&Ll();nl("LogsDatabaseV2")}
u(cm,ol);function fm(){var a=B("yt.networklessRequestController.instance");a||(a=new cm,C("yt.networklessRequestController.instance",a),P("networkless_logging")&&fl().then(function(b){a.B=b;ql(a);a.l.resolve();a.sa&&Math.random()<=a.ra&&a.B&&Pl(a.B);P("networkless_immediately_drop_sw_health_store")&&gm(a)}));
return a}
cm.prototype.writeThenSend=function(a,b){b||(b={});mj()||(this.i=!1);ol.prototype.writeThenSend.call(this,a,b)};
cm.prototype.sendThenWrite=function(a,b,c){b||(b={});mj()||(this.i=!1);ol.prototype.sendThenWrite.call(this,a,b,c)};
cm.prototype.sendAndWrite=function(a,b){b||(b={});mj()||(this.i=!1);ol.prototype.sendAndWrite.call(this,a,b)};
cm.prototype.awaitInitialization=function(){return this.l.promise};
function gm(a){var b;x(function(c){if(!a.B)throw b=Aj("clearSWHealthLogsDb"),b;return c.return(Ql(a.B).catch(function(d){a.handleError(d)}))})}
function em(a,b,c){P("use_cfr_monitor")&&hm(a,b);if(P("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(R())}c&&0===Object.keys(b).length?Tl(a):ti(a,b)}
function dm(){bm||(bm=new $l({sb:!0,lb:!0}));return bm}
function hm(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Vl().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Vl().requestComplete(a,!0);d(e,f)}}
;var im=0,jm=0,km,lm=A.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:!1,potentialEsfErrorCounter:jm};C("ytNetworklessLoggingInitializationOptions",lm);function mm(a,b){function c(d){var e=nm().F();if(!om()||!d||e&&P("vss_networkless_bypass_write"))pm(a,b);else{var f={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0};El(f,d).then(function(g){f.id=g;nm().F()&&qm(f)}).catch(function(g){qm(f);
nm().F()?Nh(g):Yl(g)})}}
b=void 0===b?{}:b;P("skip_is_supported_killswitch")?fl().then(function(d){c(d)}):c(el())}
function rm(a,b){function c(d){if(om()&&d){var e={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,l){P("use_cfr_monitor")&&Vl().requestComplete(e.url,!0);void 0!==e.id?Jl(e.id,d):f=!0;P("vss_network_hint")&&nm().R(!0);g(k,l)};
if(P("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,l){Vl().requestComplete(e.url,!1);h(k,l)}}pm(e.url,e.options);
El(e,d).then(function(k){e.id=k;f&&Jl(e.id,d)}).catch(function(k){nm().F()?Nh(k):Yl(k)})}else pm(a,b)}
b=void 0===b?{}:b;P("skip_is_supported_killswitch")?fl().then(function(d){c(d)}):c(el())}
function sm(){var a=el();if(!a)throw Aj("throttleSend");im||(im=Pe.P(function(){var b;return x(function(c){if(1==c.i)return w(c,Gl("NEW",a),2);if(3!=c.i)return b=c.j,b?w(c,qm(b),3):(Pe.Z(im),im=0,c.return());im&&(im=0,sm());c.i=0})},100))}
function qm(a){var b,c,d;return x(function(e){switch(e.i){case 1:b=el();if(!b)throw c=Aj("immediateSend"),c;if(void 0===a.id){e.v(2);break}return w(e,Hl(a.id,b),3);case 3:(d=e.j)?a=d:Oh(Error("The request cannot be found in the database."));case 2:var f=a.timestamp;if(!(2592E6<=R()-f)){e.v(4);break}Oh(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.v(5);break}return w(e,Jl(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=tm(a));f=a;if(P("use_request_time_ms_header")){var g;
if(null==f?0:null==(g=f.options)?0:g.headers)f.options.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R()))}else{var h,k;if(null==f?0:null==(h=f.options)?0:null==(k=h.postParams)?0:k.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(R())}a=f;if(!a){e.v(0);break}if(!a.skipRetry||void 0===a.id){e.v(8);break}return w(e,Jl(a.id,b),8);case 8:pm(a.url,a.options,!!a.skipRetry),e.i=0}})}
function tm(a){var b=el();if(!b)throw Aj("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g,h,k;return x(function(l){switch(l.i){case 1:P("use_cfr_monitor")&&Vl().requestComplete(a.url,!1);g=wl(f);if(!(P("nwl_consider_error_code")&&g||!P("nwl_consider_error_code")&&um()<=ii("potential_esf_error_limit",10))){l.v(2);break}if(P("skip_checking_network_on_cfr_failure")&&(!P("skip_checking_network_on_cfr_failure")||Vl().isEndpointCFR(a.url))){l.v(3);break}return w(l,nm().ka(),3);case 3:if(nm().F()){l.v(2);break}c(e,f);if(!P("nwl_consider_error_code")||void 0===
(null==(h=a)?void 0:h.id)){l.v(6);break}return w(l,Il(a.id,b,!1),6);case 6:return l.return();case 2:if(P("nwl_consider_error_code")&&!g&&um()>ii("potential_esf_error_limit",10))return l.return();B("ytNetworklessLoggingInitializationOptions")&&lm.potentialEsfErrorCounter++;jm++;if(void 0===(null==(k=a)?void 0:k.id)){l.v(8);break}return 1>a.sendCount?w(l,Il(a.id,b),12):w(l,Jl(a.id,b),8);case 12:Pe.P(function(){nm().F()&&sm()},5E3);
case 8:c(e,f),l.i=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.i)return P("use_cfr_monitor")&&Vl().requestComplete(a.url,!0),void 0===(null==(g=a)?void 0:g.id)?h.v(2):w(h,Jl(a.id,b),2);P("vss_network_hint")&&nm().R(!0);d(e,f);h.i=0})};
return a}
function nm(){if(P("use_new_nwl"))return dm();km||(km=new $l({sb:!0,lb:!0}));return km}
function pm(a,b,c){c&&0===Object.keys(b).length?Tl(a):ti(a,b)}
function om(){return B("ytNetworklessLoggingInitializationOptions")?lm.isNwlInitialized:!1}
function um(){return B("ytNetworklessLoggingInitializationOptions")?lm.potentialEsfErrorCounter:jm}
;function vm(a){var b=this;this.config_=null;a?this.config_=a:Ii()&&(this.config_=Ji());aj(function(){Yi(b)},0,5E3)}
vm.prototype.isReady=function(){!this.config_&&Ii()&&(this.config_=Ji());return!!this.config_};
function Zi(a,b,c,d){function e(y){y=void 0===y?!1:y;var z;if(d.retry&&"www.youtube-nocookie.com"!=h&&(y||P("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(z=Wi(b,c,l,k)),z)){var G=g.onSuccess,K=g.onFetchSuccess;g.onSuccess=function(M,O){Xi(z);G(M,O)};
c.onFetchSuccess=function(M,O){Xi(z);K(M,O)}}try{y&&d.retry&&!d.Ta.bypassNetworkless?(g.method="POST",d.Ta.writeThenSend?P("use_new_nwl_wts")?fm().writeThenSend(p,g):mm(p,g):P("use_new_nwl_saw")?fm().sendAndWrite(p,g):rm(p,g)):(g.method="POST",g.postParams||(g.postParams={}),ti(p,g))}catch(M){if("InvalidAccessError"==M.name)z&&(Xi(z),z=0),Oh(Error("An extension is blocking network request."));
else throw M;}z&&aj(function(){Yi(a)},0,5E3)}
!N("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Oh(new lj("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new lj("innertube xhrclient not ready",b,c,d);Nh(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(y,z){if(d.onSuccess)d.onSuccess(z)},
onFetchSuccess:function(y){if(d.onSuccess)d.onSuccess(y)},
onError:function(y,z){if(d.onError)d.onError(z)},
onFetchError:function(y){if(d.onError)d.onError(y)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.pb)&&(h=f);var k=a.config_.rb||!1,l=Qi(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var m="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,q={alt:"json"},v=a.config_.qb&&f;v=v&&f.startsWith("Bearer");v||(q.key=a.config_.innertubeApiKey);var p=fi(""+h+m,q||{},!0);P("use_new_nwl")&&fm().i||!P("use_new_nwl")&&
om()?dl().then(function(y){e(y)}):e(!1)}
;function wm(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var xm=A.ytPubsubPubsubInstance||new L,ym=A.ytPubsubPubsubSubscribedKeys||{},zm=A.ytPubsubPubsubTopicToKeys||{},Am=A.ytPubsubPubsubIsSynchronous||{};L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.na;L.prototype.publish=L.prototype.ca;L.prototype.clear=L.prototype.clear;C("ytPubsubPubsubInstance",xm);C("ytPubsubPubsubTopicToKeys",zm);C("ytPubsubPubsubIsSynchronous",Am);C("ytPubsubPubsubSubscribedKeys",ym);function Bm(a){this.policy=a;this.store=[];this.i={}}
Bm.prototype.storePayload=function(a,b){this.store.push({payload:b,keys:a});b=[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/");this.i[b]?this.i[b]++:this.i[b]=1;this.i[b]>=this.policy.maxBatchSize&&(this.policy.onBatchSizeExceeded(a),this.i[b]=0);return b};
Bm.prototype.extractMatchingEntries=function(a){for(var b=[],c=[],d=t(this.store),e=d.next();!e.done;e=d.next()){e=e.value;a:{var f=a;var g=Object.keys(f);g=t(g);for(var h=g.next();!h.done;h=g.next())if(h=h.value,e.keys[h]!==f[h]){f=!1;break a}f=!0}f?b.push(e.payload):c.push(e)}this.store=c;c=0;a=Cm(this,a);a=t(a);for(d=a.next();!d.done;d=a.next())d=d.value,c+=this.i[d],this.i[d]=0;c!==b.length&&Oh(new lj("Transport IMS extracted entries count != keyCounter sum",b.length,c));return b};
Bm.prototype.getSequenceCount=function(a){var b=Cm(this,a);a=0;b=t(b);for(var c=b.next();!c.done;c=b.next())a+=this.i[c.value];return a};
function Cm(a,b){var c=Object.keys(b),d="THIS_KEY_FIELD_NOT_FILLED",e="THIS_KEY_FIELD_NOT_FILLED",f="THIS_KEY_FIELD_NOT_FILLED";c=t(c);for(var g=c.next();!g.done;g=c.next())g=g.value,"auth"===g?d=Dm(b.auth):"isJspb"===g?e=JSON.stringify(b.isJspb):"cttAuthInfo"===g&&(f=Dm(b.cttAuthInfo));b=[];d=[d,e,f];a=t(Object.keys(a.i));for(e=a.next();!e.done;e=a.next()){e=e.value;f=e.split("/");c=!0;for(g=0;g<d.length;g++)if("THIS_KEY_FIELD_NOT_FILLED"!==d[g]&&d[g]!==f[g]){c=!1;break}c&&b.push(e)}return b}
Bm.prototype.getSequenceCount=Bm.prototype.getSequenceCount;Bm.prototype.extractMatchingEntries=Bm.prototype.extractMatchingEntries;Bm.prototype.storePayload=Bm.prototype.storePayload;function Dm(a){return void 0===a?"undefined":a}
;var Em=ii("initial_gel_batch_timeout",2E3),Fm=Math.pow(2,16)-1,Gm=void 0;function Hm(){this.l=this.i=this.j=0}
var Im=new Hm,Jm=new Hm,Km=!0,Lm=A.ytLoggingTransportGELQueue_||new Map;C("ytLoggingTransportGELQueue_",Lm);var Mm=A.ytLoggingTransportGELProtoQueue_||new Map;C("ytLoggingTransportGELProtoQueue_",Mm);var Nm=A.ytLoggingTransportTokensToCttTargetIds_||{};C("ytLoggingTransportTokensToCttTargetIds_",Nm);var Om=A.ytLoggingTransportTokensToJspbCttTargetIds_||{};C("ytLoggingTransportTokensToJspbCttTargetIds_",Om);var Pm={};
function Qm(){var a=B("yt.logging.ims");a||(a=new Bm({maxBatchSize:ii("tvhtml5_logging_max_batch")||ii("web_logging_max_batch")||100,onBatchSizeExceeded:function(b){Rm({writeThenSend:!0},void 0,b.isJspb)}}),C("yt.logging.ims",a));
return a}
function Sm(a,b){if("log_event"===a.endpoint){Tm(a);var c=Um(a);if(P("use_new_in_memory_storage")){Pm[c]=!0;var d={cttAuthInfo:c,isJspb:!1};Qm().storePayload(d,a.payload);Vm(b,[],c,!1,d)}else d=Lm.get(c)||[],Lm.set(c,d),d.push(a.payload),Vm(b,d,c)}}
function Wm(a,b){if("log_event"===a.endpoint){Tm(void 0,a);var c=Um(a,!0);if(P("use_new_in_memory_storage")){Pm[c]=!0;var d={cttAuthInfo:c,isJspb:!0};Qm().storePayload(d,a.payload.toJSON());Vm(b,[],c,!0,d)}else d=Mm.get(c)||[],Mm.set(c,d),a=a.payload.toJSON(),d.push(a),Vm(b,d,c,!0)}}
function Vm(a,b,c,d,e){d=void 0===d?!1:d;a&&(Gm=new a);a=ii("tvhtml5_logging_max_batch")||ii("web_logging_max_batch")||100;var f=R(),g=d?Jm.l:Im.l;b=b.length;e&&(b=Qm().getSequenceCount(e));b>=a?Rm({writeThenSend:!0},P("flush_only_full_queue")?c:void 0,d):10<=f-g&&(Xm(d),d?Jm.l=f:Im.l=f)}
function Ym(a,b){if("log_event"===a.endpoint){Tm(a);var c=Um(a),d=new Map;d.set(c,[a.payload]);b&&(Gm=new b);return new mg(function(e,f){Gm&&Gm.isReady()?Zm(d,Gm,e,f,{bypassNetworkless:!0},!0):e()})}}
function $m(a,b){if("log_event"===a.endpoint){Tm(void 0,a);var c=Um(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(Gm=new b);return new mg(function(e){Gm&&Gm.isReady()?an(d,Gm,e,{bypassNetworkless:!0},!0):e()})}}
function Um(a,b){var c="";if(a.ea)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new zh;c.videoId?d.setVideoId(c.videoId):c.playlistId&&hd(d,2,Ah,c.playlistId);Om[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Nm[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Rm(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new mg(function(d,e){c?(window.clearTimeout(Jm.j),window.clearTimeout(Jm.i),Jm.i=0):(window.clearTimeout(Im.j),window.clearTimeout(Im.i),Im.i=0);if(Gm&&Gm.isReady())if(P("use_new_in_memory_storage")){var f=a,g=c,h=Gm;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,l=new Map;if(void 0!==b)g?(e=Qm().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),k.set(b,e),an(k,h,d,f)):(k=Qm().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),l.set(b,k),Zm(l,
h,d,e,f));else if(g){e=t(Object.keys(Pm));for(g=e.next();!g.done;g=e.next())l=g.value,g=Qm().extractMatchingEntries({isJspb:!0,cttAuthInfo:l}),0<g.length&&k.set(l,g),Pm[l]=!1;an(k,h,d,f)}else{k=t(Object.keys(Pm));for(g=k.next();!g.done;g=k.next()){g=g.value;var m=Qm().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0!==m.length&&l.set(g,m)}Zm(l,h,d,e,f)}}else f=a,k=c,h=Gm,f=void 0===f?{}:f,k=void 0===k?!1:k,void 0!==b?k?(e=new Map,k=Mm.get(b)||[],e.set(b,k),an(e,h,d,f),Mm.delete(b)):(k=new Map,
l=Lm.get(b)||[],k.set(b,l),Zm(k,h,d,e,f),Lm.delete(b)):k?(an(Mm,h,d,f),Mm.clear()):(Zm(Lm,h,d,e,f),Lm.clear());else Xm(c),d()})}
function Xm(a){a=void 0===a?!1:a;if(P("web_gel_timeout_cap")&&(!a&&!Im.i||a&&!Jm.i)){var b=Xh(function(){Rm({writeThenSend:!0},void 0,a)},6E4);
a?Jm.i=b:Im.i=b}window.clearTimeout(a?Jm.j:Im.j);b=N("LOGGING_BATCH_TIMEOUT",ii("web_gel_debounce_ms",1E4));P("shorten_initial_gel_batch_timeout")&&Km&&(b=Em);b=Xh(function(){Rm({writeThenSend:!0},void 0,a)},b);
a?Jm.j=b:Im.j=b}
function Zm(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(R()),h=a.size;a=t(a);for(var k=a.next();!k.done;k=a.next()){var l=t(k.value);k=l.next().value;var m=l.next().value;l=k;k=ob({context:Ki(b.config_||Ji())});if(!Ma(m)&&!P("throw_err_when_logevent_malformed_killswitch")){d();break}k.events=m;(m=Nm[l])&&bn(k,l,m);delete Nm[l];l="visitorOnlyApprovedKey"===l;cn(k,g,l);dn(e);m=function(){h--;h||c()};
var q=function(){h--;h||c()};
try{Zi(b,"log_event",k,en(e,l,m,q,f)),Km=!1}catch(v){Nh(v),d()}}}
function an(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(R()),g=a.size,h=new Map([].concat(ia(a)));h=t(h);for(var k=h.next();!k.done;k=h.next()){var l=t(k.value).next().value,m=a.get(l);k=new Bh;var q=Pi(b.config_||Ji());I(k,gh,1,q);m=m?fn(m):[];m=t(m);for(q=m.next();!q.done;q=m.next())nd(k,3,wh,q.value);(m=Om[l])&&gn(k,l,m);delete Om[l];l="visitorOnlyApprovedKey"===l;hn(k,f,l);dn(d);k=rd(k);l=en(d,l,function(){g--;g||c()},function(){g--;
g||c()},e);
l.headers["Content-Type"]="application/json+protobuf";l.postBodyFormat="JSPB";l.postBody=k;Zi(b,"log_event","",l);Km=!1}}
function dn(a){P("always_send_and_write")&&(a.writeThenSend=!1)}
function en(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,Ta:a,ea:b,Rb:!!e,headers:{},postBodyFormat:"",postBody:""};P("use_request_time_ms_header")&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(R())));return a}
function cn(a,b,c){P("use_request_time_ms_header")||(a.requestTimeMs=String(b));P("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=N("EVENT_ID"))&&(c=jn(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function hn(a,b,c){P("use_request_time_ms_header")||H(a,2,b);if(!c&&(b=N("EVENT_ID"))){c=jn();var d=new yh;H(d,1,b);H(d,2,c);I(a,yh,5,d)}}
function jn(){var a=N("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*Fm/2));a++;a>Fm&&(a=1);Hh("BATCH_CLIENT_COUNTER",a);return a}
function bn(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function gn(a,b,c){if(fd(c,1===id(c,Ah)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;I(a,zh,4,c);a=jd(a,gh,1)||new gh;c=jd(a,eh,3)||new eh;var e=new dh;e.setToken(b);H(e,1,d);nd(c,12,dh,e);I(a,eh,3,c)}
function fn(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new wh(a[c]))}catch(d){Nh(new lj("Transport failed to deserialize "+String(a[c])))}return b}
function Tm(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);C("yt.logging.transport.scrapedPayloadsForTesting",c)}}
;var kn=A.ytLoggingGelSequenceIdObj_||{};C("ytLoggingGelSequenceIdObj_",kn);function ln(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=wm();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};P("log_sequence_info_on_gel_web")&&d.la&&(a=e.context,b=d.la,b={index:mn(b),groupKey:b},a.sequence=b,d.mb&&delete kn[d.la]);(d.vb?Ym:Sm)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,ea:d.ea},c)}
function nn(a){Rm(void 0,void 0,void 0===a?!1:a)}
function mn(a){kn[a]=a in kn?kn[a]+1:0;return kn[a]}
;var on=A.ytLoggingGelSequenceIdObj_||{};C("ytLoggingGelSequenceIdObj_",on);function pn(a){var b=void 0;b=void 0===b?{}:b;var c=!1;N("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);c=c?null:vm;b=void 0===b?{}:b;var d=Math.round(b.timestamp||R());H(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=wm();d=new vh;H(d,1,b.timestamp||!isFinite(e)?-1:e);if(P("log_sequence_info_on_gel_web")&&b.la){e=b.la;var f=mn(e),g=new uh;H(g,2,f);H(g,1,e);I(d,uh,3,g);b.mb&&delete on[b.la]}I(a,vh,33,d);(b.vb?$m:Wm)({endpoint:"log_event",payload:a,cttAuthInfo:b.cttAuthInfo,ea:b.ea},c)}
;function qn(a,b){var c=void 0===c?{}:c;if(P("migrate_events_to_ts")){c=void 0===c?{}:c;var d=vm;N("ytLoggingEventsDefaultDisabled",!1)&&vm===vm&&(d=null);ln(a,b,d,c)}else d=vm,N("ytLoggingEventsDefaultDisabled",!1)&&vm==vm&&(d=null),ln(a,b,d,c)}
;var rn=[{Ca:function(a){return"Cannot read property '"+a.key+"'"},
va:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ca:function(a){return"Cannot call '"+a.key+"'"},
va:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ca:function(a){return a.key+" is not defined"},
va:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var tn={W:[],U:[{hb:sn,weight:500}]};function sn(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function un(){this.U=[];this.W=[]}
var vn;function wn(){if(!vn){var a=vn=new un;a.W.length=0;a.U.length=0;tn.W&&a.W.push.apply(a.W,tn.W);tn.U&&a.U.push.apply(a.U,tn.U)}return vn}
;var xn=new L;function yn(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=zn(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=zn(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=zn(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function zn(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function An(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Bn(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=yn(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Bn(e+".ve",f,g,h):0;d+=g;d+=Bn(e,a[e],b,c);if(500<d)break}}else c[b]=Cn(a),d+=c[b].length;else c[b]=Cn(a),d+=c[b].length;return d}
function Bn(a,b,c,d){c+="."+a;a=Cn(b);d[c]=a;return c.length+a.length}
function Cn(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Dn=new Set,En=0,Fn=0,Gn=0,Hn=[],In=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function Jn(){for(var a=t(In),b=a.next();!b.done;b=a.next()){var c=Lb();if(c&&0<=c.toLowerCase().indexOf(b.value.toLowerCase()))return!0}return!1}
;function Kn(){var a;return x(function(b){return(a=hf())?b.return(a.then(function(c){c=rd(c);for(var d=[],e=0,f=0;f<c.length;f++){var g=c.charCodeAt(f);255<g&&(d[e++]=g&255,g>>=8);d[e++]=g}return yc(d,3)})):b.return(Promise.resolve(null))})}
;var Ln={};function Mn(a){return Ln[a]||(Ln[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Nn={},On=[],Dg=new L,Pn={};function Qn(){for(var a=t(On),b=a.next();!b.done;b=a.next())b=b.value,b()}
function Rn(a,b){var c;"yt:"===a.tagName.toLowerCase().substr(0,3)?c=a.getAttribute(b):c=a?a.dataset?a.dataset[Mn(b)]:a.getAttribute("data-"+b):null;return c}
function Sn(a){Dg.ca.apply(Dg,arguments)}
;function Tn(a){this.i=a||{};a=[this.i,window.YTConfig||{}];for(var b=0;b<a.length;b++)a[b].host&&(a[b].host=a[b].host.toString().replace("http://","https://"))}
function Un(a,b){a=[a.i,window.YTConfig||{}];for(var c=0;c<a.length;c++){var d=a[c][b];if(void 0!==d)return d}return null}
function Vn(a,b,c){Wn||(Wn={},Wh(window,"message",function(d){a:{if(d.origin===Un(a,"host")){try{var e=JSON.parse(d.data)}catch(f){e=void 0;break a}if(d=Wn[e.id])d.A=!0,d.A&&(D(d.u,d.sendMessage,d),d.u.length=0),d.Ja(e)}e=void 0}return e}));
Wn[c]=b}
var Wn=null;var Xn=window;function Yn(a,b,c){this.s=this.i=this.j=null;this.l=0;this.A=!1;this.u=[];this.m=null;this.J={};if(!a)throw Error("YouTube player element ID required.");this.id=Qa(this);this.H=c;this.setup(a,b)}
n=Yn.prototype;n.setSize=function(a,b){this.i.width=a.toString();this.i.height=b.toString();return this};
n.getIframe=function(){return this.i};
n.Ja=function(a){Zn(this,a.event,a)};
n.addEventListener=function(a,b){var c=b;"string"===typeof b&&(c=function(){window[b].apply(window,arguments)});
if(!c)return this;this.m.subscribe(a,c);$n(this,a);return this};
function ao(a,b){b=b.split(".");if(2===b.length){var c=b[1];a.H===b[0]&&$n(a,c)}}
n.destroy=function(){this.i&&this.i.id&&(Nn[this.i.id]=null);var a=this.m;a&&"function"==typeof a.dispose&&a.dispose();if(this.s){a=this.i;var b=a.parentNode;b&&b.replaceChild(this.s,a)}else(a=this.i)&&a.parentNode&&a.parentNode.removeChild(a);Wn&&(Wn[this.id]=null);this.j=null;a=this.i;for(var c in mb)mb[c][0]==a&&Uh(c);this.s=this.i=null};
n.Ma=function(){return{}};
function bo(a,b,c){c=c||[];c=Array.prototype.slice.call(c);b={event:"command",func:b,args:c};a.A?a.sendMessage(b):a.u.push(b)}
function Zn(a,b,c){a.m.l||(c={target:a,data:c},a.m.ca(b,c),Sn(a.H+"."+b,c))}
function co(a,b){var c=document.createElement("iframe");b=b.attributes;for(var d=0,e=b.length;d<e;d++){var f=b[d].value;null!=f&&""!==f&&"null"!==f&&c.setAttribute(b[d].name,f)}c.setAttribute("frameBorder","0");c.setAttribute("allowfullscreen","1");c.setAttribute("allow","accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture");c.setAttribute("title","YouTube "+Un(a.j,"title"));(b=Un(a.j,"width"))&&c.setAttribute("width",b.toString());(b=Un(a.j,"height"))&&c.setAttribute("height",
b.toString());var g=a.Ma();g.enablejsapi=window.postMessage?1:0;window.location.host&&(g.origin=window.location.protocol+"//"+window.location.host);g.widgetid=a.id;window.location.href&&D(["debugjs","debugcss"],function(k){var l=$b(window.location.href,k);null!==l&&(g[k]=l)});
Xn.yt_embedsTokenValue&&(g.embedsTokenValue=encodeURIComponent(Xn.yt_embedsTokenValue),delete Xn.yt_embedsTokenValue);var h=""+Un(a.j,"host")+("/embed/"+Un(a.j,"videoId"))+"?"+Ub(g);Xn.yt_embedsEnableUaChProbe?Kn().then(function(k){var l=new URL(h),m=Number(l.searchParams.get("reloads"));isNaN(m)&&(m=0);l.searchParams.set("reloads",(m+1).toString());k&&l.searchParams.set("uach",k);l.searchParams.set("uats",Math.floor(window.performance.timeOrigin).toString());k=Od(l.href).toString();Bd(c,Pd(k));return k}):
Xn.yt_embedsEnableIframeSrcWithIntent?Bd(c,Pd(h)):c.src=h;
return c}
n.Ua=function(){this.i&&this.i.contentWindow?this.sendMessage({event:"listening"}):window.clearInterval(this.l)};
function eo(a){Vn(a.j,a,a.id);a.l=Yh(a.Ua.bind(a));Wh(a.i,"load",function(){window.clearInterval(a.l);a.l=Yh(a.Ua.bind(a))})}
n.setup=function(a,b){var c=document;if(a="string"===typeof a?c.getElementById(a):a)if(c="iframe"===a.tagName.toLowerCase(),b.host||(b.host=c?Sb(a.src):"https://www.youtube.com"),this.j=new Tn(b),c||(b=co(this,a),this.s=a,(c=a.parentNode)&&c.replaceChild(b,a),a=b),this.i=a,this.i.id||(this.i.id="widget"+Qa(this.i)),Nn[this.i.id]=this,window.postMessage){this.m=new L;eo(this);b=Un(this.j,"events");for(var d in b)b.hasOwnProperty(d)&&this.addEventListener(d,b[d]);for(var e in Pn)Pn.hasOwnProperty(e)&&
ao(this,e)}};
function $n(a,b){a.J[b]||(a.J[b]=!0,bo(a,"addEventListener",[b]))}
n.sendMessage=function(a){a.id=this.id;a.channel="widget";var b=JSON.stringify(a),c=[Sb(this.i.src||"").replace("http:","https:")];if(this.i.contentWindow)for(var d=0;d<c.length;d++)try{this.i.contentWindow.postMessage(b,c[d])}catch(Vb){if(Vb.name&&"SyntaxError"===Vb.name){if(!(Vb.message&&0<Vb.message.indexOf("target origin ''"))){var e=void 0,f=Vb;e=void 0===e?{}:e;e.name=N("INNERTUBE_CONTEXT_CLIENT_NAME",1);e.version=N("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=e||{},h="WARNING";h=void 0===h?"ERROR":
h;if(f){f.hasOwnProperty("level")&&f.level&&(h=f.level);if(P("console_log_js_exceptions")){var k=f,l=[];l.push("Name: "+k.name);l.push("Message: "+k.message);k.hasOwnProperty("params")&&l.push("Error Params: "+JSON.stringify(k.params));k.hasOwnProperty("args")&&l.push("Error args: "+JSON.stringify(k.args));l.push("File name: "+k.fileName);l.push("Stacktrace: "+k.stack);window.console.log(l.join("\n"),k)}if(!(5<=En)){var m=void 0,q=void 0,v=f,p=g,y=ge(v),z=y.message||"Unknown Error",G=y.name||"UnknownError",
K=y.stack||v.j||"Not available";if(K.startsWith(G+": "+z)){var M=K.split("\n");M.shift();K=M.join("\n")}var O=y.lineNumber||"Not available",lb=y.fileName||"Not available",tc=K,wa=0;if(v.hasOwnProperty("args")&&v.args&&v.args.length)for(var qa=0;qa<v.args.length&&!(wa=An(v.args[qa],"params."+qa,p,wa),500<=wa);qa++);else if(v.hasOwnProperty("params")&&v.params){var Y=v.params;if("object"===typeof v.params)for(q in Y){if(Y[q]){var da="params."+q,ea=Cn(Y[q]);p[da]=ea;wa+=da.length+ea.length;if(500<wa)break}}else p.params=
Cn(Y)}if(Hn.length)for(var X=0;X<Hn.length&&!(wa=An(Hn[X],"params.context."+X,p,wa),500<=wa);X++);navigator.vendor&&!p.hasOwnProperty("vendor")&&(p["device.vendor"]=navigator.vendor);var S={message:z,name:G,lineNumber:O,fileName:lb,stack:tc,params:p,sampleWeight:1},Mj=Number(v.columnNumber);isNaN(Mj)||(S.lineNumber=S.lineNumber+":"+Mj);if("IGNORED"===v.level)m=0;else a:{for(var Nj=wn(),Oj=t(Nj.W),Lf=Oj.next();!Lf.done;Lf=Oj.next()){var Pj=Lf.value;if(S.message&&S.message.match(Pj.Sb)){m=Pj.weight;
break a}}for(var Qj=t(Nj.U),Mf=Qj.next();!Mf.done;Mf=Qj.next()){var Rj=Mf.value;if(Rj.hb(S)){m=Rj.weight;break a}}m=1}S.sampleWeight=m;for(var Sj=t(rn),Nf=Sj.next();!Nf.done;Nf=Sj.next()){var Of=Nf.value;if(Of.va[S.name])for(var Tj=t(Of.va[S.name]),Pf=Tj.next();!Pf.done;Pf=Tj.next()){var Uj=Pf.value,Rd=S.message.match(Uj.regexp);if(Rd){S.params["params.error.original"]=Rd[0];for(var Qf=Uj.groups,Vj={},Wb=0;Wb<Qf.length;Wb++)Vj[Qf[Wb]]=Rd[Wb+1],S.params["params.error."+Qf[Wb]]=Rd[Wb+1];S.message=Of.Ca(Vj);
break}}}S.params||(S.params={});var Wj=wn();S.params["params.errorServiceSignature"]="msg="+Wj.W.length+"&cb="+Wj.U.length;S.params["params.serviceWorker"]="false";A.document&&A.document.querySelectorAll&&(S.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));yb("sample").constructor!==xb&&(S.params["params.fconst"]="true");var sa=S;window.yterr&&"function"===typeof window.yterr&&window.yterr(sa);if(0!==sa.sampleWeight&&!Dn.has(sa.message)){if("ERROR"===h){xn.ca("handleError",
sa);if(P("record_app_crashed_web")&&0===Gn&&1===sa.sampleWeight)if(Gn++,P("errors_via_jspb")){var Rf=new th;H(Rf,1,1);if(!P("report_client_error_with_app_crash_ks")){var Xj=new oh;H(Xj,1,sa.message);var Yj=new ph;I(Yj,oh,3,Xj);var Zj=new qh;I(Zj,ph,5,Yj);var ak=new rh;I(ak,qh,9,Zj);I(Rf,rh,4,ak)}var ko=Rf,bk=new wh;ld(bk,th,20,xh,ko);pn(bk)}else{var ck={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};P("report_client_error_with_app_crash_ks")||(ck.systemHealth={crashData:{clientError:{logMessage:{message:sa.message}}}});
qn("appCrashed",ck)}Fn++}else"WARNING"===h&&xn.ca("handleWarning",sa);if(P("kevlar_gel_error_routing"))a:{var Sf=void 0,Tf=void 0,Ic=h,Q=sa;if(P("errors_via_jspb")){if(Jn())Tf=void 0;else{var Xb=new lh;H(Xb,1,Q.stack);Q.fileName&&H(Xb,4,Q.fileName);var Na=Q.lineNumber&&Q.lineNumber.split?Q.lineNumber.split(":"):[];0!==Na.length&&(1!==Na.length||isNaN(Number(Na[0]))?2!==Na.length||isNaN(Number(Na[0]))||isNaN(Number(Na[1]))||(H(Xb,2,Number(Na[0])),H(Xb,3,Number(Na[1]))):H(Xb,2,Number(Na[0])));var sb=
new oh;H(sb,1,Q.message);H(sb,3,Q.name);H(sb,6,Q.sampleWeight);"ERROR"===Ic?H(sb,2,2):"WARNING"===Ic?H(sb,2,1):H(sb,2,0);var Uf=new mh;H(Uf,1,!0);ld(Uf,lh,3,nh,Xb);var tb=new ih;H(tb,3,window.location.href);for(var dk=N("FEXP_EXPERIMENTS",[]),Vf=0;Vf<dk.length;Vf++){var ek=tb,lo=dk[Vf];Tc(ek);gd(ek,5,2,!1).push(lo)}var Wf=Ih();if(!Jh()&&Wf)for(var fk=t(Object.keys(Wf)),ub=fk.next();!ub.done;ub=fk.next()){var gk=ub.value,Xf=new kh;H(Xf,1,gk);Xf.setValue(String(Wf[gk]));nd(tb,4,kh,Xf)}var Yf=Q.params;
if(Yf){var hk=t(Object.keys(Yf));for(ub=hk.next();!ub.done;ub=hk.next()){var ik=ub.value,Zf=new kh;H(Zf,1,"client."+ik);Zf.setValue(String(Yf[ik]));nd(tb,4,kh,Zf)}}var jk=N("SERVER_NAME"),kk=N("SERVER_VERSION");if(jk&&kk){var $f=new kh;H($f,1,"server.name");$f.setValue(jk);nd(tb,4,kh,$f);var ag=new kh;H(ag,1,"server.version");ag.setValue(kk);nd(tb,4,kh,ag)}var Sd=new ph;I(Sd,ih,1,tb);I(Sd,mh,2,Uf);I(Sd,oh,3,sb);Tf=Sd}var lk=Tf;if(!lk)break a;var mk=new wh;ld(mk,ph,163,xh,lk);pn(mk)}else{if(Jn())Sf=
void 0;else{var Jc={stackTrace:Q.stack};Q.fileName&&(Jc.filename=Q.fileName);var Oa=Q.lineNumber&&Q.lineNumber.split?Q.lineNumber.split(":"):[];0!==Oa.length&&(1!==Oa.length||isNaN(Number(Oa[0]))?2!==Oa.length||isNaN(Number(Oa[0]))||isNaN(Number(Oa[1]))||(Jc.lineNumber=Number(Oa[0]),Jc.columnNumber=Number(Oa[1])):Jc.lineNumber=Number(Oa[0]));var bg={level:"ERROR_LEVEL_UNKNOWN",message:Q.message,errorClassName:Q.name,sampleWeight:Q.sampleWeight};"ERROR"===Ic?bg.level="ERROR_LEVEL_ERROR":"WARNING"===
Ic&&(bg.level="ERROR_LEVEL_WARNNING");var mo={isObfuscated:!0,browserStackInfo:Jc},Yb={pageUrl:window.location.href,kvPairs:[]};N("FEXP_EXPERIMENTS")&&(Yb.experimentIds=N("FEXP_EXPERIMENTS"));var cg=Ih();if(!Jh()&&cg)for(var nk=t(Object.keys(cg)),vb=nk.next();!vb.done;vb=nk.next()){var ok=vb.value;Yb.kvPairs.push({key:ok,value:String(cg[ok])})}var dg=Q.params;if(dg){var pk=t(Object.keys(dg));for(vb=pk.next();!vb.done;vb=pk.next()){var qk=vb.value;Yb.kvPairs.push({key:"client."+qk,value:String(dg[qk])})}}var rk=
N("SERVER_NAME"),sk=N("SERVER_VERSION");rk&&sk&&(Yb.kvPairs.push({key:"server.name",value:rk}),Yb.kvPairs.push({key:"server.version",value:sk}));Sf={errorMetadata:Yb,stackTrace:mo,logMessage:bg}}var tk=Sf;if(!tk)break a;qn("clientError",tk)}if("ERROR"===Ic||P("errors_flush_gel_always_killswitch"))b:if(P("migrate_events_to_ts"))c:{if(P("web_fp_via_jspb")&&(nn(!0),!P("web_fp_via_jspb_and_json")))break c;nn()}else{if(P("web_fp_via_jspb")&&(nn(!0),!P("web_fp_via_jspb_and_json")))break b;nn()}}if(!P("suppress_error_204_logging")){var wb=
sa,Kc=wb.params||{},Ya={urlParams:{a:"logerror",t:"jserror",type:wb.name,msg:wb.message.substr(0,250),line:wb.lineNumber,level:h,"client.name":Kc.name},postParams:{url:N("PAGE_NAME",window.location.href),file:wb.fileName},method:"POST"};Kc.version&&(Ya["client.version"]=Kc.version);if(Ya.postParams){wb.stack&&(Ya.postParams.stack=wb.stack);for(var uk=t(Object.keys(Kc)),eg=uk.next();!eg.done;eg=uk.next()){var vk=eg.value;Ya.postParams["client."+vk]=Kc[vk]}var fg=Ih();if(fg)for(var wk=t(Object.keys(fg)),
gg=wk.next();!gg.done;gg=wk.next()){var xk=gg.value;Ya.postParams[xk]=fg[xk]}var yk=N("SERVER_NAME"),zk=N("SERVER_VERSION");yk&&zk&&(Ya.postParams["server.name"]=yk,Ya.postParams["server.version"]=zk)}ti(N("ECATCHER_REPORT_HOST","")+"/error_204",Ya)}try{Dn.add(sa.message)}catch(ro){}En++}}}}}else throw Vb;}else console&&console.warn&&console.warn("The YouTube player is not attached to the DOM. API calls should be made after the onReady event. See more: https://developers.google.com/youtube/iframe_api_reference#Events")};function fo(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function go(a){return 0===a.search("get")||0===a.search("is")}
;function ho(a,b){Yn.call(this,a,Object.assign({title:"video player",videoId:"",width:640,height:360},b||{}),"player");this.N={};this.playerInfo={};this.videoTitle=""}
u(ho,Yn);n=ho.prototype;n.Ma=function(){var a=Un(this.j,"playerVars");if(a){var b={},c;for(c in a)b[c]=a[c];a=b}else a={};window!==window.top&&document.referrer&&(a.widget_referrer=document.referrer.substring(0,256));if(c=Un(this.j,"embedConfig")){if(Pa(c))try{c=JSON.stringify(c)}catch(d){console.error("Invalid embed config JSON",d)}a.embed_config=c}return a};
n.Ja=function(a){var b=a.event;a=a.info;switch(b){case "apiInfoDelivery":if(Pa(a))for(var c in a)a.hasOwnProperty(c)&&(this.N[c]=a[c]);break;case "infoDelivery":io(this,a);break;case "initialDelivery":Pa(a)&&(window.clearInterval(this.l),this.playerInfo={},this.N={},jo(this,a.apiInterface),io(this,a));break;default:Zn(this,b,a)}};
function io(a,b){if(Pa(b)){for(var c in b)b.hasOwnProperty(c)&&(a.playerInfo[c]=b[c]);a.playerInfo.hasOwnProperty("videoData")&&(b=a.playerInfo.videoData,b.hasOwnProperty("title")&&b.title?(b=b.title,b!==a.videoTitle&&(a.videoTitle=b,a.i.setAttribute("title",b))):(a.videoTitle="",a.i.setAttribute("title","YouTube "+Un(a.j,"title"))))}}
function jo(a,b){D(b,function(c){this[c]||("getCurrentTime"===c?this[c]=function(){var d=this.playerInfo.currentTime;if(1===this.playerInfo.playerState){var e=(Date.now()/1E3-this.playerInfo.currentTimeLastUpdated_)*this.playerInfo.playbackRate;0<e&&(d+=Math.min(e,1))}return d}:fo(c)?this[c]=function(){this.playerInfo={};
this.N={};bo(this,c,arguments);return this}:go(c)?this[c]=function(){var d=0;
0===c.search("get")?d=3:0===c.search("is")&&(d=2);return this.playerInfo[c.charAt(d).toLowerCase()+c.substr(d+1)]}:this[c]=function(){bo(this,c,arguments);
return this})},a)}
n.getVideoEmbedCode=function(){var a=Un(this.j,"host")+("/embed/"+Un(this.j,"videoId")),b=Number(Un(this.j,"width")),c=Number(Un(this.j,"height"));if(isNaN(b)||isNaN(c))throw Error("Invalid width or height property");b=Math.floor(b);c=Math.floor(c);var d=this.videoTitle;Hb.test(a)&&(-1!=a.indexOf("&")&&(a=a.replace(Bb,"&amp;")),-1!=a.indexOf("<")&&(a=a.replace(Cb,"&lt;")),-1!=a.indexOf(">")&&(a=a.replace(Db,"&gt;")),-1!=a.indexOf('"')&&(a=a.replace(Eb,"&quot;")),-1!=a.indexOf("'")&&(a=a.replace(Fb,
"&#39;")),-1!=a.indexOf("\x00")&&(a=a.replace(Gb,"&#0;")));return'<iframe width="'+b+'" height="'+c+'" src="'+a+'" title="'+((null!=d?d:"YouTube video player")+'" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>')};
n.getOptions=function(a){return this.N.namespaces?a?this.N[a]?this.N[a].options||[]:[]:this.N.namespaces||[]:[]};
n.getOption=function(a,b){if(this.N.namespaces&&a&&b&&this.N[a])return this.N[a][b]};
function no(a){if("iframe"!==a.tagName.toLowerCase()){var b=Rn(a,"videoid");b&&(b={videoId:b,width:Rn(a,"width"),height:Rn(a,"height")},new ho(a,b))}}
;C("YT.PlayerState.UNSTARTED",-1);C("YT.PlayerState.ENDED",0);C("YT.PlayerState.PLAYING",1);C("YT.PlayerState.PAUSED",2);C("YT.PlayerState.BUFFERING",3);C("YT.PlayerState.CUED",5);C("YT.get",function(a){return Nn[a]});
C("YT.scan",Qn);C("YT.subscribe",function(a,b,c){Dg.subscribe(a,b,c);Pn[a]=!0;for(var d in Nn)Nn.hasOwnProperty(d)&&ao(Nn[d],a)});
C("YT.unsubscribe",function(a,b,c){Cg(a,b,c)});
C("YT.Player",ho);Yn.prototype.destroy=Yn.prototype.destroy;Yn.prototype.setSize=Yn.prototype.setSize;Yn.prototype.getIframe=Yn.prototype.getIframe;Yn.prototype.addEventListener=Yn.prototype.addEventListener;ho.prototype.getVideoEmbedCode=ho.prototype.getVideoEmbedCode;ho.prototype.getOptions=ho.prototype.getOptions;ho.prototype.getOption=ho.prototype.getOption;
On.push(function(a){var b=a;b||(b=document);a=hb(b.getElementsByTagName("yt:player"));var c=b||document;if(c.querySelectorAll&&c.querySelector)b=c.querySelectorAll(".yt-player");else{var d;c=document;b=b||c;if(b.querySelectorAll&&b.querySelector)b=b.querySelectorAll(".yt-player");else if(b.getElementsByClassName){var e=b.getElementsByClassName("yt-player");b=e}else{e=b.getElementsByTagName("*");var f={};for(c=d=0;b=e[c];c++){var g=b.className,h;if(h="function"==typeof g.split)h=0<=cb(g.split(/\s+/),
"yt-player");h&&(f[d++]=b)}f.length=d;b=f}}b=hb(b);D(gb(a,b),no)});
"undefined"!=typeof YTConfig&&YTConfig.parsetags&&"onload"!=YTConfig.parsetags||Qn();var oo=A.onYTReady;oo&&oo();var po=A.onYouTubeIframeAPIReady;po&&po();var qo=A.onYouTubePlayerAPIReady;qo&&qo();}).call(this);
